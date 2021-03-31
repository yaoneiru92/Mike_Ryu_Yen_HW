
Time Series Analysis Conclusions

Based on my time series analysis results, I would not buy the yen now. Both the ARMA and the ARIMA model have p-values that are greater than .05 (.42 and .65, respectively). Therefore, the coefficient for the autoregressive term is not statistically significant and should not be kept in the models. 

Futhermore, the upward-trending GARCH Model shows us that the exchange rate risk is expected to increase which a more conservative investor may not be comfortable with the level of risk. 

I would not base my decisions solely on the results of these models. Before using them, I would need to improve the models and make them statistically significant. I would also consider other aspects and models before I feel confident in using these models.


Regression Analysis Conclusion

The out-of-sample RMSE (.42) is lower than the in-sample RMSE (.60).RMSE is usually lower for training data, but is higher in my analysis. 

This meant that my model made better predictions on data it has never seen before which is the test set over the actual training set. Therefore, I would not trust these predictions until I develop a new and better model.