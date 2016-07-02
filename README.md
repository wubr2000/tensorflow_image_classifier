# Image Classifer for Real Estate Photos using Tensorflow

I followed [this O'Reilly tutorial](https://www.oreilly.com/learning/tensorflow-for-poets) to train an image classifier for real estate photos using Tensorflow.

The first version of the model is based on Inception trained with ImageNet photos. I've retrained the final layer with a set of real estate images that have nine different labels (bathroom, bedroom, closet, dining room, etc). The overal accuracy of the first version is 84.6%.

Future improvements include:
* Using other topologies: e.g. VGGNet, MXNet (which are better for localized images)
* Using other base training datasets: e.g. MIT Places dataset (better for location, architecture, room images)
* Tweaking model hyperparameters (e.g. learning rate, training batch size), input distortions (to make training more robust), size of training/test set (control for overfitting).
