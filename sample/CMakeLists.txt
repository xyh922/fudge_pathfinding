add_executable(astar_grid_map astar_grid_map.cc)
add_executable(astar_jump_point astar_jump_point.cc)
add_executable(astar_sliding_puzzle astar_sliding_puzzle.cc)
add_executable(dijkstra_water_jug dijkstra_water_jug.cc)
add_executable(astar_multi_agent_map astar_multi_agent_map.cc)
add_executable(astar_torches_puzzle astar_torches_puzzle.cc)

include_directories("../include")
	
SET(CMAKE_CXX_FLAGS "-std=c++0x")

