# Sports Classification

Classify sports images into one of 6 classes: ["Basketball", "Football", "Rowing", "Swimming", "Tennis", "Yoga"].

you can clone this repo or use [google colab](https://colab.research.google.com/drive/1uXPZB-MktblUK6v_s2wRBpLxpXIhiPNd?usp=sharing)

## Dataset
Unfortunately the dataset used does not provide ground truth labels for the test set and is small in size. However it suffices to perform general experiments. 
You can find the dataset [here](https://drive.google.com/file/d/14Sj_XBz-6O0T3mIOfL3629lJuQNHMlMM/view?usp=share_link)

## Models
Experiments have been made with custom models (fcnn1, fcnn2, fcnn3) which are made up of convolution, pooling and dense layers.
Implementations of [VGG16](https://arxiv.org/abs/1409.1556), and [AlexNet](https://www.researchgate.net/publication/267960550_ImageNet_Classification_with_Deep_Convolutional_Neural_Networks)


## Results
While there are no ground truths available in the used dataset, manual inspection of the results showed that fcnn1 performed the best with the current configurations.
