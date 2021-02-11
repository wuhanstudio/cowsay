from building import *
import rtconfig

# get current directory
cwd     = GetCurrentDir()
# The set of source files associated with this SConscript file.
src     = Glob('cowsay.c')

LOCAL_CCFLAGS = ''

group = DefineGroup('cowsay', src, depend = ['PKG_USING_COWSAY'], LOCAL_CCFLAGS = LOCAL_CCFLAGS)

Return('group')
