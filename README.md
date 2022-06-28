# driver_availability
internship project, summer 2022

ESTIMATING DRIVER AVAILABILITY 

 

Project description 

Estimating a probability with a margin for error for a given driver that he/she will be available for delivery pickups during a particular slot time on a forthcoming day 

Type of problem 

Time series forecasting problem majorly 

Can also implement ML algorithms on data to check credibility 

RNNs, LSTMs 

Data: 

Hourly spark activity of driver 

Number of minutes spent (main variable) 

Add multiple variables later for multivariate analysis 

DRVR_APPLN_ACTV is the most important table to work on 

Useful Algorithms discovered until now 

fbprophet 

xgboost 

tbats 

Complexities 

Every driver will have a unique pattern 

To scale the forecasting/regression problem of estimating one driver’s activity to N drivers 

Suitable error metrics 

mae (cannot deal with outliers) 

rmse (good for data with outliers) 

mape (ideal for most TS problems but is weird with zero values) 
