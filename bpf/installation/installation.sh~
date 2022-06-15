sudo apt install build-essential git make libelf-dev clang strace tar bpfcc-tools linux-headers-$(uname -r) gcc-multilib
sudo apt install clang llvm
sudo apt install -y build-essential flex bison libssl-dev libelf-dev
# running example python ebpf: 
# one approach is to run it simply like a python script else you can do something such below
sudo strace -e bpf python3 listen.py

# if you dont want to download another version of kernel you can use the /usr/src/{headers, ...}
# you can check for /usr/src/linux-headers-$(uname -r)/tools/bpf/Makefile for suitable one for your system
