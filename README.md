# manifest-hub
# manifest-hub
# manifest-hub

export REPO_URL='https://mirrors.tuna.tsinghua.edu.cn/git/git-repo/'
mkdir -p ~/bin
curl "${REPO_URL}"repo -o ~/bin/repo
chmod a+x ~/bin/repo



repo init -u git@github.com:without1022/manifest-hub.git -b main -m manifest.xml
