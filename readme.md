#cd到项目根目录
git init #生成.git文件夹
git add . #添加项目中所有文件到待上传列表中
git config --global user.email "2356940823@qq.com" #自己的github邮箱
git config --global user.name "zhaohaowu" #自己的github用户名
git commit -m "carto_test" #注释的语句可以随意写
git remote add origin git@github.com:zhaohaowu/carto_test.git #自己的git仓库
git push origin master #本地上传到github
git pull origin master #github拉取到本地
