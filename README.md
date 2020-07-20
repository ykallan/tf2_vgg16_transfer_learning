# tf2_vgg16_transfer_learning
tensorflow2， 使用vgg16迁移学习识别cifar10数据集


double_train 训练了vgg网络以及后面的自定义全连接层，然后又单独训练了一下后面的全连接层，不过提升不大，

no_train 只训练了后面的全连接层部分，效果不是很理想

train_vgg 训练了vgg网络以及后面的全连接层部分，训练集准确率达到0.97， 验证机能达到0.84，还算能看

peace
