cmake_minimum_required(VERSION 3.9)
project(udacity_cpp_histogram_filter_project)

set(CMAKE_CXX_STANDARD 11)

add_executable(udacity_cpp_histogram_filter_project
        debugging_helpers.cpp
        helpers.cpp
        localizer.cpp
        simulate.cpp
        tests.cpp)
