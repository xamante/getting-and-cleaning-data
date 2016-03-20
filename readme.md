#The R file run_analysis.R does the following:

Download the dataset provided it is not already in your working directory
Loads the activity and feature info into R
Loads  the training and test datasets, keeping only those variables relating to a mean or standard deviation
Loads the activity and subject data for each dataset, and merges those columns with the dataset
Merges the two datasets into one
Converts the activity and subject columns into factors
Outputs in the working directory a tidy dataset with the mean value of each variable for each subject and activity pair.
This can be found in file tidied.txt.