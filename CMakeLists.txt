cmake_minimum_required(VERSION 3.8)
project(hello_world_with_github_actions)
set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.c)

add_executable(main ${SOURCE_FILES})