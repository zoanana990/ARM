
BASEINCLUDE ?= /lib/modules/`uname -r`/build

mydemo_fasync-objs := mydemodrv_fasync.o 

obj-m	:=   mydemo_fasync.o
all : 
	$(MAKE) -C $(BASEINCLUDE) M=$(PWD) modules;

clean:
	$(MAKE) -C $(BASEINCLUDE) M=$(PWD) clean;
	rm -f *.ko;


