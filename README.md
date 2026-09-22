Embodied Agentic Harnesses for Physical Intelligence A Survey

Yu Huang*, Yue Chen&, Zijiang Yang#, Gary Ding^

*: Institute of Advanced Technology, University of Science and Technology of China, China 

#: School of Computer Science & Technology, University of Science and Technology of China, China 

&: Futurewei Technology Inc., San Jose, USA

^: Dartmouth College

Abstract

Embodied agents depend on more than the capabilities of a language, vision-language, or action model. They
require a runtime that grounds observations, coordinates executable capabilities, monitors outcomes, and
manages intervention when physical execution diverges from a plan. This survey examines embodied agentic
harnesses as this runtime control plane. We distinguish four logical responsibilities—reasoning, runtime
governance, skill execution, and hardware interfacing—and separate essential execution services from optional
prediction, persistent memory, and adaptation mechanisms. A contract-based formulation connects skill
preconditions, resource ownership, interruption, postconditions, and trace collection without assuming that every
system implements an identical stack. We organize the literature by mechanisms rather than publication period:
grounding and composition, state and memory, scheduling and coordination, verification and recovery, and
adaptation. Complementary descriptors record the execution interface, intervention timescale, adaptation target,
and evidence setting. The synthesis connects LLM and agent foundations, VLA policies, world models, and
predictive-action models to affordance-based planning, programmatic control, memory-guided orchestration,
agent operating systems, and evolving runtime critics. It distinguishes operational harnesses from infrastructure
for robot learning and deployment. We further distinguish semantic task verification, invocation authority, and
physical safety assurance, which require different evidence. The resulting synthesis identifies execution
contracts, compositional evaluation, bounded adaptation, and explicit human authority as priorities for reliable
long-horizon physical intelligence.
