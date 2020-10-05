# Future sales prediction
Got this data from Kaggle, this is not meant for time-series predictions, but want to experiment to see if we could get a relative good prediction out of time-series models.

## Conclusion
After several attempts, using both ARIMA and Prophet, we concluded this data is not ideal for time-serie predictions. We attempted removing outliers to make sure the data represents a general trend of the sales behavior, but still could not make the models to make accurate prediction. 

We can conclude that there are not enough trends presented in the data, this could be due to the company was constantly making random changes to their maketing strategies, making the sales data preseting random behaviors. Or the company replies purely on organic grow and there isn't enought data presented in the provided dataset for accurate time-series predictions.

In conclusion, time-series is not a good approach for this data, should use other means, regression or CNN.
