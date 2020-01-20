# RNN-implementation
Experiment with various types of recurrent neural networks in PyTorch

## Encoder Implementation: Classifying Names with a Character-Level RNN
Compared the accuracy of the encoder when varying the type of hidden units: 
 - linear units
 - gated recurrent units (GRUs)
 - long short term memory (LSTM) units 


## Decoder Implementation: Generating Names with a Character-Level RNN
        
Compared the accuracy of the decoder when varying the information fed as input to the hidden units at each time step: 
 - i) previous hidden unit, previous character and category; 
 - ii) previous hidden unit and previous character; 
 - iii) previous hidden unit and category; 
 - iv) previous hidden unit. 

## Seq2seq implementation: Translation with a Sequence to Sequence Model with Attention

Compared the accuracy of the seq2seq model with and without attention. 
