# YOLOR在kitti上的fine-tune

转换kitti格式到yolo，构建kitti.yaml、kitti.names（不一定需要，但保险起见还是构建了）

直接执行train.py

输出的precision和recall，是将conf定在0.1计算的，并且判断TP的iou阈值是0.5