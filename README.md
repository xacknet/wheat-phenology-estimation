# wheat-phenology-estimation
This repository contains code for monitoring wheat growth &amp; climate impact using satellite NDVI in South Asia, using machine learning techniques for data analysis and visualization.
## Methodology
Our work uses satellite time-series data acquisition, preprocessing and NDVI masking for time-series analysis. The calculated NDVI
is followed through cubic spline and SG filter. Offline change point detection is applied using Ruptures model with parameter
tuning on 2021-2022 and testing on 2020-2021. The obtained multi-year phenological results are validated against in-field
phenological dates. The results are correlated with rate of change in weather data, smoothed at 15 and 90 day interval using
moving average and cubic spline for in-depth correlation analysis between weather and phenology.
