# simple-poerty-creator  
##简易古诗生成器  

*****

###初期版本  
* 对古诗句素材库进行关键词提取，储存为语料库，生成器根据生成诗句的格式从语料库随机抽取相应词项；  
* 生成古诗的质量完全取决于素材库的素材质量；  

###后期更新版本（TODO）  
* 词项单元储存为 {词项名，词数，平仄，尾音韵母，风格倾向} 数据结构，持久储存为JSON，XML或数据库文件；  
* 升级预料库后，根据词项单元的平仄，尾韵母，风格倾向等信息，随机组合词项中加入组合权重；
* 诗句生成模式分为：5言绝句，5言律诗，7言绝句，7言律诗，根据不同诗句特点组合词项；
