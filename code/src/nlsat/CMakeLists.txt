z3_add_component(nlsat
  SOURCES
    nlsat_clause.cpp
    nlsat_evaluator.cpp
    nlsat_explain.cpp
    nlsat_interval_set.cpp
    nlsat_solver.cpp
    nlsat_types.cpp
    nlsat_dynamic.cpp
  COMPONENT_DEPENDENCIES
    polynomial
    sat
  PYG_FILES
    nlsat_params.pyg
)
