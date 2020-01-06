# piGHBPred
Prediction of Growth hormone binding proteins, via Novel Consensus Feature Selection and PSSM profile
# A Brief
piGHBPred  a new bioinformatics predictor and feature selection tool, for targeting Growth hormone binding proteins sequence solely. 
piGHBPred, first encode the features through via different feature extraction techniques in a federated feature source. Then we ensemble feature selected via Tune Grid Model to make consensus features with PSSM Profile features

## Feature Used
- CTD (Composition Transition Distribution
- Pseudo AAC (Amino Acid Composition)
- Geray
- Moran
- APSeAAC


## Algorithm
- Classification Classical Classifier with different keranl functions, and AAN yeilds the best out comes, of them all.

## Getting Started

Following are list of todo, before making run of the propose model.

### Prerequisites
#####  Following are the lib need to be installed....
What things you need to install the software and how to install them
- python3.6  [follow](https://www.python.org/downloads/release/python-367/)
- keras 2.2.4 [follow](https://keras.io/)
- Flask 1.0.2 [follow](http://flask.pocoo.org/docs/0.12/installation/)
- scikit-learn 0.19.1 [follow](https://scikit-learn.org/stable/install.html)
- scipy 1.1.0 [follow](https://scipy.org/install.html)
- numpy1.15.4 [follow](https://docs.scipy.org/doc/numpy/user/install.html)
- matplotlib3.0.2 [follow](https://matplotlib.org/users/installing.html#building-on-windows/)
- tensorflow 1.12.0 [follow](https://www.tensorflow.org/hub/installation)

```
$pip install <lib_name>
```

### Evaluate a model.

```
EvaluateModel.py
```
EvaluateModel.py is used for Evaluating a pre-trained model, stored for each successive layeres 1&2.


### Making prediction.

```
ModelPrediction.py
```
ModelPrediction.py is used to use to Obtained class probibilities for successive Layeres 1&2 on feeding and unseen Fasta Sequence or Sequence File.


This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Inspiration.
