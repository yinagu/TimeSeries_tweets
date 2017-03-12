## Time Series Analysis of Pokémon GO User Activity on Twitter

- Web-scrapped 275,000+ tweets and analyzed the hourly tweet counts during Jan.8th - 25th, 2017
The project consists following steps:
- Loading and handling time series data
- Checked time series **stationarity** by statistical Dickey-Fuller tes.
- Estimating and eliminating **trend** by moving average and exponential weighted moving average
- Inspecting **seasonality** by Autocorrelation Function (ACF) and Fourier Transform (FT)
- Seasonal decomposition
- Forcasting the time series by sinusoidal, autoregression (AR), moving-average (MA), autoregressive-moving-average (ARMA), autoregressive-integrated-moving-average (ARIMA) models.
