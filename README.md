# Household-Power-Cunsumption-Prediction
`Dataset`: KAG_energydata_complete.csv <br>
`Available from`: https://www.kaggle.com/datasets/loveall/appliances-energy-prediction/data

The data set is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods. The energy data was logged every 10 minutes with m-bus energy meters. Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru), and merged together with the experimental data sets using the date and time column.<br>
Two random variables have been included in the data set for testing the regression models and to filter out non-predictive attributes (parameters).

### Varibles Information:

`date`: year-month-day hour:minute:second<br>
`Appliances`: energy use in Wh<br>
`lights`:  energy use of light fixtures in the house in Wh<br>
`T1`: Temperature in kitchen area, in Celsius<br>
`RH1`: Humidity in kitchen area, in %<br>
`T2`: Temperature in living room area, in Celsius<br>
`RH2`: Humidity in living room area, in %<br>
`T3`: Temperature in laundry room area<br>
`RH3`: Humidity in laundry room area, in %<br>
`T4`:  Temperature in office room, in Celsius<br>
`RH4`: Humidity in office room, in %<br>
`T5`:  Temperature in bathroom, in Celsius<br>
`RH5`: Humidity in bathroom, in %<br>
`T6`: Temperature outside the building (north side), in Celsius<br>
`RH6`: Humidity outside the building (north side), in %<br>
`T7`: Temperature in ironing room , in Celsius<br>
`RH7`: Humidity in ironing room, in %<br>
`T8`: Temperature in teenager room 2, in Celsius<br>
`RH8`: Humidity in teenager room 2, in %<br>
`T9`: Temperature in parents room, in Celsius<br>
`RH9`: Humidity in parents room, in %<br>
`Tout`: Temperature outside (from Chievres weather station), in Celsius<br>
`Pressure`: (from Chievres weather station), in mm Hg<br>
`RHout`: Relative Humidity outside (from Chievres weather station), in %<br>
`Wind speed`: (from Chievres weather station), in m/s<br>
`Visibility`: (from Chievres weather station), in km<br>
`Tdewpoint`: Dew point temperature (from Chievres weather station), Â°C<br>
`rv1`: Random variable 1, non-dimensional(whether use it or not)<br>
`rv2`: Random variable 2, non-dimensional(whether use it or not)<br>
