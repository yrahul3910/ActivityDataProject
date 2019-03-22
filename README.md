# Human Activity Project
This is a project that uses my time logging data of around 9 months. The project has three parts: 

* The first part tries to analyze my most productive hours by defining what activities are considered productive. 
* The second part tries to build a predictive model to based on the past 5 activities. This uses a 2-layer LSTM model, and is simple enough to train reasonably quickly on a CPU. It was trained on a AMD A8 CPU, and took around 6 seconds per epoch.
* The third part analyzes the efficiency of a new sleep cycle, using the Welch's t-test for independent samples. Specifically, it checks if there is a statistically significant difference between the means of the work done per day across both sleep cycles, where the newer sleep cycle is, roughly, from 8:30 PM to 3:30 AM.
