# Simplifying-Graph-Convolutional-Networks 简化的图神经网络 (SGC)
A reference code for paper : [*Simplifying Graph Convolutional Networks*](https://arxiv.org/abs/1902.07153) ( **SGC** for short ) based Keras and tensorflow. 

## Usage
Before to execute this algorithm, it is necessary to install these required packages shown in the file named ' requirements.txt '. The default dataset is Cora Network and the detail description can be found in the file data. Just execute the following command from the project home directory :

    $ python SGC.py

Our implementation can match the benchmark described in the original paper and the GPU will be used if available.
**Note: the default splits of the training set in my implementation are different from that in original papar, which you can find in the authors' code.**

## References 
For a more detail explanation of the SGC, have a look at the relative  references about the SGC and vanilla GCN:

1. [Wu F, Zhang T, Holanda de Souza A, et al. Simplifying graph convolutional networks[J]. ICML 2019.](https://arxiv.org/abs/1902.07153)
2. https://github.com/Tiiiger/SGC
3. [Thomas N. Kipf, Max Welling, Semi-Supervised Classification with Graph Convolutional Networks. ICLR 2017.](http://arxiv.org/abs/1609.02907)

4. <https://github.com/zhouchunpong/GCN_Keras>




