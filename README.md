# Spectral Density Estimation and SARIMA Modeling

This project conducts an empirical time series investigation comprising two analytical tasks:
1. **Passenger Demand Analysis & Forecasting:** Evaluating spectral density via Fast Fourier Transform (FFT) and smoothed Daniell kernels, stationarizing trend-dominated data through first-order differencing, and generating short-term forecasts for early 2026 using an optimal ARIMA model.
2. **Climate Noise Modeling:** Deconstructing 85 years (1940–2024, $N = 1020$) of monthly average surface temperature data for Poland, eliminating strong annual seasonality via lag-12 difference operators ($\nabla_{12}$), verifying stationarity via Augmented Dickey-Fuller (ADF) tests, and identifying a SARIMA noise model with white-noise residuals.



## Project Structure
* Time series source files (`AKW-12.csv`, `average-monthly-surface-temperature.csv`)
* Source R Markdown implementation (`tsa.Rmd`)
* Generated HTML report (`tsa.html`)


## Authors
* Aneta Buszta
* Katarzyna Gołąb
* Wioletta Sudoł
* Anna Wygoda
