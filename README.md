# dnn_network_generator  
Hypothesis: Generating network architectures and training for a small number of epoch will let you quickly find good architectures and filter out bad ones.    
In this experiment we use FMNIST dataset and convolutional neural networks.  
This code generates different network architectures (cnn), then evaluates them against each other.  
270 different models are generated using 2 epochs and different architectures, then the top and bottom 10 are fully trained to evaluate them against each other.  
The top and bottom 10 are evaluated against a baseline and some cnns found on kaggle. 
Correlation between model architecture and validation accuracy is seen.  
