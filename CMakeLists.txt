cmake_minimum_required(VERSION 3.20)
project(hello C)

set(CMAKE_C_STANDARD 17)

if(WIN32)
    add_compile_options(-fexec-charset=GBK)
endif()

add_executable(untitled main.c)
