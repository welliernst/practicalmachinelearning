# practicalmachinelearning
assignment solution is rather lean. 
Problem
Quality of weight-lifting was asessessed by a competent trainer.    
The problem was to predict the judgement of the trainer from sensor data.    
Raw measurements were simultaneous measurements magnetometer, accelerometer   and gyroscope data from belt, arm, glove and dumbbell.  
Data from sequential measurements were averaged using a sliding window  
(see article below). Calculated data were yaw, pitch ann roll.  
Usind a random forrest with ten-fold cross-validation we achieved good accuracy (0.9992) in the training data set.   
Prediction was performed in the test data.  
