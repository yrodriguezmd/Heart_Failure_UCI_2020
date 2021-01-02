# Heart_Failure_UCI_2020

This project used data uploaded from the UCI Machine Learning Repository (Heart Failure clinical records Data Set), donated on 2020-02-05.  There are 13 attributes and 299 instances, with no missing values.

The data contained both categorical and continuous variables.

Each variable was analyzed individually, and were binned as needed.

Bivariate and Multivariate Analyses were done primarily through the groupby method.

Modelling for Mortality utilized Feature Importances, Naive-Bayes, K Nearest Neighbors, Random Forest Classification and Logistic Regression.

What follows is a copy of the abstract.  The full manuscript is available in a separate file.



#Prediction of Heart Failure Mortality using Machine Learning Algorithms


#Rodriguez M, 2021, January.


#Abstract

Background

Heart failure continues to present a significant burden on the health system globally.  Despite the availability of multiple studies, guidelines, novel medications and technology, the outlook remains poor.

Methodology

A dataset comprising of 13 attributes (including mortality) and 299 instances, collected from admitted heart failure patients in a single institution on 2015 was used.  Uni-, bi- and multivariate analyses were performed using sklearn and pandas modules on a Jupyter platform.  Linear regression was performed on Ejection Fraction (EF) and age.  Modelling was assessed using various attributes on Naive-Bayes, k Nearest Neighbor, Random Forest Classifier and Logistic Regression.

Results

The mean age was 60+/-11 years, and 65% were male.  Overall mortality was 32%.  Mortality was associated with advanced age, hypertension, decreased EF, anemia, low platelet counts <=100, creatinine >200 mg/dL, low serum sodium <=130 mEq/L, mildly elevated creatinine phosphokinase (CK) (200-500 mcg/L) and markedly elevated CK (>=3000 mcg/L), and short duration of follow-up (< 60 days).  Differences in sex, smoking and diabetes status had no effect on mortality.  Mortality can be modelled using age, EF and serum creatinine using Naive-Bayes, Random Forest Classifier and Logistic Regression, with an average accuracy score of 75%.

Conclusion

Machine Learning (ML) algorithms can provide acceptable modelling for mortality among heart failure patients.  There is a good possibility that utilization of unsupervised ML techniques may provide insights on previously undetected risk factors and relationships.

Keywords:  heart failure, heart disease, prediction, mortality, machine learning
