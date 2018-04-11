# problems_on_tfstudy
python C:/Users/doublewudi/PycharmProjects/tensorflow/tensorflow" "framework/slim/train_image_classifier.py ^
--train_dir=C:/Users/doublewudi/PycharmProjects/tensorflow/tensorflow" "framework/slim/model ^
--dataset_name=myimages ^
--dataset_split_name=train ^
--dataset_dir=D:\images ^
--batch_size=10 ^
--max_number_of_steps=10000 ^
--model_name=inception_v3 ^
--clone_on_cpu=true ^
pause

1.train_image_classifier.py里面
tf.app.flags.DEFINE_string的意义
2.工程文件路径不要建立在C盘下面，路径中不要加空格
