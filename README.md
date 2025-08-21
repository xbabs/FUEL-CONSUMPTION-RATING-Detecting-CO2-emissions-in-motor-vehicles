# CO₂ Emissions — Fuel Consumption Ratings

Linear/Multiple Regression to model CO₂ emissions from vehicle attributes.

Reduced fuel consumption is thus an important step toward combating climate change and promoting sustainable development. However, a machine learning model was developed to predict and analyze CO2 emissions.


To develop this model, a simple and multiple linear regression machine learning algorithm was performed. Prior to that, some data training and testing was carried out using the scikit-learn library. The CO2 emission (y_train) is the dependent variable and the independent variables comprise the x_train dataset (model year, engine size, cylinders, and fuel consumption). However, a method was used to split, reshape, and rescale the numerical variables. The data was divided into training and testing datasets, and the variables were reshaped so that they are all the same shape and size. Finally, the numerical variables was rescaled using the min-max scaling method to ensure that all values are within a similar range. This will help to improve the model's accuracy.


RESULT:

The performance of each model was compared by measuring its accuracy, precision and recall. The "vehicle make" yields the highest accuracy, precision, and recall (0.96) as shown in the code file. This is because it provides overall information about fuel consumption rating. Also, the "fuel type" has an average precision, accuracy and recall of 91% because it is considered as the direct measure to CO2 emissions. However, the "vehicle model" has the least and is clearly not a good measure for predicting fuel consumption ratings.

## Files
`Fuel_Consumption_Ratings for CO2 emissions.ipynb`, `MY2010-2014 Fuel Consumption Ratings 5-cycle.csv`.

## Run
