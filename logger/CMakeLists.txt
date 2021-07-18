cmake_minimum_required(VERSION 3.10.0)
project(yh_logger)

set (CMAKE_CXX_FLAGS "--std=c++17")

add_library(yh_logger Log.cpp)