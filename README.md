Code for an article on propositional logic as the language of if-then-else or case expressions.

logic.py and utils.py go with the first half. Then
ttt_tabulate.py/ttt_tabule_3way.py. bdd.py goes with the rest.

Generalized to n-way decisions, in nway_logic.py and dd.py.

lua/ has a LuaJIT port, to check for reasonable performance when not
stuck with CPython.

Other files are for testing and other demos, e.g. puzzler.py.
