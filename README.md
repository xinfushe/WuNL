# WuNL
ffmpeg+opengl

boost asio接收rtp流，过滤后送到解码模块解码，解码模块将解完的YUV压入队列，显示模块读取队列进行显示

20路rtp流输入，输出是1/4/9/16分屏，要能调整分屏数量

当前状态：boost asio模块、解码模块完成，显示模块正在优化，笔记本性能有限，目前仅解码第一路，将结果复制显示两次

下一步工作：更多路的显示，显示的切换等等，主要还是OPENGL的学习
