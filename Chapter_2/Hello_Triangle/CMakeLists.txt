#find_package(Threads)
add_executable( Hello_Triangle Hello_Triangle.c )
target_link_libraries( Hello_Triangle Common )
#target_link_libraries( Hello_Triangle Common ${CMAKE_THREAD_LIBS_INIT})
