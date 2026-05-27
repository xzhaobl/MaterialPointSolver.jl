# AGENTS.md

This repository is being audited only as a high-level architectural reference.

Do not modify source code unless explicitly requested.

Do not translate Julia code into MATLAB.

## Project context

The goal is to design a MATLAB minimal production MPM host for geotechnical liquefaction modelling and possible future THM or staged multiphysics MPM problems.

## Audit focus

Focus only on:

1. modular solver architecture;
2. particle fields and user-defined fields;
3. material model interface;
4. scalar and tensor internal-variable support;
5. how custom particle-level state variables are added;
6. staged or multiphysics extension ideas;
7. ideas useful for a MATLAB research-code design;
8. ideas that are too Julia-specific or over-engineered for MATLAB.
Also note whether existing material examples demonstrate scalar or tensor particle-state persistence, because this is relevant for later Liao state-variable storage.

## Expected output

Keep the audit concise. Do not analyse every file. Return a high-level architectural report and MATLAB design recommendations.
