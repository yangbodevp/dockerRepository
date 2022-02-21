# dockerRepository


---

### mysql5.7

- 在window for docker启动时，会自动创建/data目录，若volumn中的路径已经存在data文件夹，则会报错`[ERROR] --initialize specified but the data directory has files in it. Aborting.`且无法启动
 
 
- 在linux中，对mysql/data和config 赋予可读写权限后直接启动compose即可