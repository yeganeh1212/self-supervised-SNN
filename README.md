# self-supervised-SNN
master's thesis _ self-supervised learning on spiking neural network

research question :

Try to build an AI tool using self-supervised learning method on a spiking neural network in order to use unlabeled image datasets for supervised tasks in one way, with self supervised method. and use less energy and storage in another way, by using SNNs.

research method :

step 1 : build a spiking neural network using [snnTorch](https://snntorch.readthedocs.io/en/latest/) package and test the network with supervised tasks on MNIST and CIFAR10 datasets

step 2 :build a self-supervised structure (http://proceedings.mlr.press/v119/chen20j/chen20j.pdf)

step 3 : use SNN as main network in self-supervised structure and test the network.
