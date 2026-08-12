ccflags-y += -DATOMISP_POSTFIX=\"css2300\" -DISP2300 -DCSS15
CSS15 := m
ISP2300 := y
postfix := css2300

include $(srctree)/$(src)/../Makefile.common

# The vendor AtomISP source predates current host compilers.  Keep its
# warnings visible while allowing this diagnostic-only module rebuild.
ccflags-y += -Wno-error
