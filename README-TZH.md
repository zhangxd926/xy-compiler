udo apt-get install flex
sudo apt-get install bison
sudo apt-get install llvm-3.8-dev

export C_INCLUDE_PATH=/usr/include/llvm-c-3.8/:$C_INCLUDE_PATH
export CPLUS_INCLUDE_PATH=/usr/include/llvm-3.8/:$CPLUS_INCLUDE_PATH
export CPLUS_INCLUDE_PATH=/usr/include/llvm-3.8/:/usr/include/llvm-c-3.8/:$CPLUS_INCLUDE_PATH

sudo apt-get install zlib1g-dev

sudo ln -s /usr/lib/llvm-3.8/bin/llvm-config /usr/bin/llvm-config
