# Predicting Heart Failure Survival

### Problem Definition

Heart failure, also known as congestive heart failure, occurs when our heart muscle doesn't pump blood as well as it should. Its  one of the leading cause of death globally, taking estimated 17 million lives each year. Certain conditions, such as narrowed arteries in our heart (coronary artery disease) or high blood pressure, gradually leave your heart too weak or stiff to fill and pump efficiently.

Not all conditions that lead to heart failure can be reversed, but treatments if started in time, can improve the signs and symptoms of heart failure and help us live longer. Lifestyle changes — such as exercising, reducing sodium in your diet, managing stress and losing weight — can improve our quality of life.

Dataset of 299 patients and 13 features was chosen for this study. Machine Learning classifiers were applied to predict patient survival and rank the features corresponding to the most important risk factors.

Death event feature was the target in this binary classification study, suggested if the patient survived or died before the end of the follow up time, which was 130 days on average.  
In the dataset, patients those were alive (death event = 0) were 203, while the patients who were dead (death event = 1) were 96 constituting 67.89% and 32.11% respectively. 

### Data Collection

heart_failure_clinical_records_dataset.csv :Dataset was loaded to pandas dataframe and analysed. The dataset consisted of data from 299 patients for 13 variables. DEATH_EVENT was target variable, 6 numerical and 6 categorical variables.

### Clean Data
 This dataset was pretty clean. Dataset did not have duplicates or null values.
 
### Exploratory Data Analysis


