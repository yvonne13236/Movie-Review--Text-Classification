# Movie-Review--Text-Clasification
This is a practice script that followed the article here: https://realpython.com/python-keras-text-classification/#choosing-a-data-set. 


It's a Jupyter Notebook script on text analysis for practice and learning purposes.

There are three movie review sources: Amazon, IMDB and Yelp

For text preprocessing, Keras's Tokenizer is used to vectorize a text corpus into a list of integers.

The final model is trained with a convolutional neural network. 

Hyperparamter tuning is done using randomized grid search (RandomizedSearchCV). The hyperparameters tuned are: vocab_size, num_filters, laxlen,kernel_size and embedding_dim.



Final performance:
Test accuracy on each dataset reaches around 83%. 



