# Understanding-and-predicting-blight-compliance

## Introduction
According to a 2020 study conducted by the University of Michigan on the Detroit community, nearly three quarters of respondents reported blighted properties in their area.[¹](https://detroitsurvey.umich.edu/wp-content/uploads/2021/02/Blight-Report-7-21-2020.pdf) Blight is a situation where owners fail to maintain their property resulting in either danger of the building collapsing, the building potentially being a hub for immoral acts or deemed unsanitary for human inhabitation.[²](https://detroitmi.gov/departments/law-department/blight) As a result, residents in neighborhoods of blighted properties report lower neighborhood satisfaction and lower perceived safety.[¹](https://detroitsurvey.umich.edu/wp-content/uploads/2021/02/Blight-Report-7-21-2020.pdf) This is a serious issue affecting the city of Detroit, so each year the city issues millions of dollars in fines to owners of blighted properties, but many of these remain unpaid. Since enforcing blight is tedious and costly, it would be useful to understand and predict blight ticket compliance so that the city council can be more effective at enforcing blight fines.

This project is the fourth assignment in the Applied Machine Learning in Python course[³](https://www.coursera.org/learn/python-machine-learning) by the University of Michigan offered through Coursera.

## Aims
1. Predict the probability of blight ticket compliance given a number of input features such as judgement amount.
2. Understand the relationship between the input features and blight ticket compliance to understand why people might fail to comply.
3. With the understanding of what causes low blight compliance, the city could take action on these factors to ensure payments are made on time.

As the rate of compliance increases, the city could fund more blight remediation programs.

## Data description (Found in the input files folder)
1. train.zip - tickets issued from 2004 to 2011
2. test.csv - tickets issued from 2012 to 2016
3. address.csv - file containing the ticket IDs and corresponding addresses
4. latlons.csv -  file containing addresses and corresponding coordinates (latitude and longitude)

## Report (Found in the report folder)
A 7 page report detailing:
1. Data processing steps (Reduced the number of input features, introduced time to hearing as a new feature and converted categorical data into numerical data.)
2. Exploratory data analysis exploring the relationship between various input features and compliance.
3. The model evaluation metrics chosen.
4. The performance of Logistic Regression as a baseline model, followed by Random Forest Classifier and XGBoost Classifier as more accurate models.
5. Important features for prediction
6. Results and Actionable Takeaways
