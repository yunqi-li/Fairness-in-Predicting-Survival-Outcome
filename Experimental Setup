## Experimental Setup
We use the implementation of SGDClassifer from scikit-learn 
package to run Logistic Regression, SVM, and Perceptron. 
Since the MLPClassifier of the scikit-learn package does not 
support the weighted loss function, we implement MLP with PyTorch. 
The learning rate is set to 0.005 and 𝑙2 regularization weight is 10−6.
We choose 64 as the batch size for each active sampling step and 
run 5,000 active sampling iterations for the entire training stage. 
For MLP, we use a 2-layer neural network with hidden size (10, 5) 
with ReLU as the activation function. The learning rate is set to 0.001
with 𝑙2 regularization weight 10−4. For TCGA dataset, we set the 
trade-off parameter 𝑝 as 5%, while for SEER-18 dataset, we set the 
trade-off parameter 𝑝 as 20%, since the performance gap between patient 
groups of the SEER-18 dataset is very large, and it is more likely for
the model to focus on only one group on this dataset. The results in
section 4.3.2 are obtained with weights w_0 = 1.6, w_1 = 0.6 for Boost Neg., 
and weights w_0 = 0.8, w_1 = 1.4 for Boost Pos. on SEER-18; weights w_0 = 2.0, 
w_1 = 0.1 for Boost Neg., and weights w_0 = 0.1, w_1 = 2.0 for Boost Pos. on TCGA.
