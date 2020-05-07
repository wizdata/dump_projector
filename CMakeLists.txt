cmake_minimum_required(VERSION 3.16)

project(exe_to_swf)

add_executable(exe_to_swf exe_to_swf.c)

install(TARGETS exe_to_swf)

enable_testing()
add_test(NAME exe_to_swf COMMAND exe_to_swf)
