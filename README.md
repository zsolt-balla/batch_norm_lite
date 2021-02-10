# batch_norm_lite
In this experiment I test whether using batch norm on only a few layers of a convolutional neural network can yield a disproportionately large part of the benefits, making the process more computationally efficient.

I started exploring this topic in the summer of 2020 under the guidance of [András Horváth](https://scholar.google.com/citations?user=b-73SCcAAAAJ) who was doing [research](https://arxiv.org/abs/2010.08251) on this at the time.

[UPDATE]
My first inspections were focused on the rapid convergence in the very beginning of the training process, but I will move on to compare the final test accuracy of promising architectures on this same task - then move onto deeper networks and classification tasks more complex than MNIST.
