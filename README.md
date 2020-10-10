# The SAMPL7 Blind Prediction Challenges for Computational Chemistry
[![DOI](https://zenodo.org/badge/184310568.svg)](https://zenodo.org/badge/latestdoi/184310568)


Challenge details, inputs, and (eventually) results for the SAMPL7 series (phase) of challenges. Each individual SAMPL7 challenge may be broken up into multiple stages.

See the [SAMPL website](https://samplchallenges.github.io) for information on the Statistical Assessment of the Modeling of Proteins and Ligands (SAMPL) series of challenges as a whole. This repository focuses specifically on the SAMPL7 series of challenges. Additionally, see the SAMPL community on Zenodo for content related to the SAMPL series of challenges. If you wish to use Zenodo to post your presentation slides, datasets, and/or other SAMPL related material, and get a DOI for them, please upload to the community [here](https://zenodo.org/communities/sampl/?page=1&size=20) so that your content will be listed.

Because these files are available publicly, we have no record of who downloads them. Therefore, you should sign up for notifications. Specifically, if you want to receive updates if we uncover any problems, it is imperative that you either (a) sign up for the SAMPL e-mail list, or (b) sign up for notifications of changes to this GitHub repository (the Watch button, above); ideally you would do both.
Join our [SAMPL7 e-mail list](http://eepurl.com/gpBBun) to get e-mails with SAMPL7-related announcements.

## Upcoming workshop

We're running a [2020 SAMPL virtual workshop on Nov. 4](https://www.gdch.de/gcc2020) in combination with the GCC.  It’s timed so both European and US folks can join, and will be hot on the heels of the current SAMPL7 physical properties challenge. Sign up if you're interested in attending.

## What's here
- [Challenge Overview](#challenge-overview)
- Final information on the TrimerTrip host-guest challenge components in the `host_guest/Isaacs_clip` directory, and experimental values in the `host_guest/Analysis/ExperimentalMeasurements` directory. The Isaacs' group's publication on this is in the *New Journal of Chemistry*, [DOI 10.1039/C9NJ05336K](https://dx.doi.org/10.1039/C9NJ05336K)
- Final information on the Gibb octa acid-based challenge ("Gibb deep cavity cavitand" (GDCC) challenge) in the `host_guest/GDCC_and_guests` directory.
- Final information on the cyclodextrin derivatives challenge in the `host_guest/cyclodextrin_derivatives` directory and in our [host-guest challenge description](host_guest_description.md).
- Results for host-guest reference calculations (alchemical binding free energy calculations with YANK) conducted by Mobley lab in the `host_guest/Analysis/Submissions/TrimerTrip`, `host_guest/Analysis/Submissions/GDCC`, and `host_guest/Analysis/Submissions/CD`. Reference calculations were not formal challenge submissions.
- Experimental details for the CD challenge in [host_guest_description.md](host_guest_description.md)
- [Host-guest participation instructions](host_guest_instructions.md) with information on the submission format, etc. Our submission system is also [now available](http://sampl-submission.us-west-1.elasticbeanstalk.com/submit/). Submission formats are available in the subdirectories for the individual host-guest systems.
- Protein-ligand details on the [PHIP2 stage 1-3 challenges](protein_ligand/README.md), in the `protein_ligand` directory.
- [PHIP2 challenge stage 1-3 submission instructions](protein_ligand_instructions.md), in the `protein_ligand_instructions.md` file.
- [Details of the SAMPL7 physical property challenge](physical_property/) on log *P*, pK<sub>a</sub> and permeability. Input files, instructions, submission formats, and example submission formats are available in the subdirectories for the individual challenges.
- SAMPL7 physical property submission instructions and submission server links ([SAMPL7 pKa submission](http://sampl-submit.us-west-1.elasticbeanstalk.com/submit/SAMPL7-pKa), [SAMPL7 logP/permeability submission](http://sampl-submit.us-west-1.elasticbeanstalk.com/submit/SAMPL7-physprop))
- SAMPL7 physical properties experimental values, in [`physical_property/experimental_data'](physical_property/experimental_data)

The SAMPL7 physical property challenge is now open! All three host-guest challenges are now closed, as are the three stages of the PHIP2 protein-ligand challenge. Note the first phase of the SAMPL8 host-guest challenge is now open on the SAMPL8 GitHub repo.

## What's coming
- PHIPA analysis
- Physical properties submissions
- Physical properties analysis

## Disclaimers:
- As usual, we make no warranty as to correctness of protonation states, tautomers, conformations and poses provided in these directories. In some cases the most relevant such states may not be known, or multiple states perhaps should be considered. Please exercise caution and due diligence.
- We make an effort to indicate which files are original source files, and which are derived files, so that participants can refer to the original source files to help resolve any uncertainties. We encourage participants to do so.
- While we make every effort to ensure correctness of the files we provide, it is not uncommon for there to be some errors. **Please sign up for our [e-mail list](http://eepurl.com/gpBBun)**, since if any critical bugs are found, we will e-mail out appropriate announcements.

## Changes and Data Set Versions

### Release versions
- **Release 0.1** (July 22, 2019): Finalizes all three host-guest systems and provides sdf, mol2 and PDB files for all guests. Fixes several critical bugs, including **fixing several incorrect cyclodextrin-derivative host structure files**, **fixing errors in a draft TrimerTrip structure file**, **fixing the SMILES string for TrimerTrip guest `g15`**, and **finalizing TrimerTrip guest list**.
- **Release 0.1.1** (July 22, 2019, DOI [10.5281/zenodo.3346023](https://dx.doi.org/10.5281/zenodo.3346023)): Includes updated README files that should have been in release 0.1.
- **Release 0.1.2** (Sept. 16, 2019, DOI [10.5281/zenodo.3432298](https://dx.doi.org/10.5281/zenodo.3432298)): Fixes protonation states for three "modified cyclodextrin" hosts which had accidentally been prepared (and drawn in ChemDraw) with charged groups present as neutral -- specifically terminal -NH3 groups were provided as -NH2. This affected MGLab19, 24 and 34. Also includes minor maintenance fixes -- listing final rather than tentative buffer conditions for GDCC case (just removing the "tentative" on the buffer identity, and correcting pH from 11.5 to 11.7); updates submission deadlines; fixes missing coordinates in TrimerTrip `g11`; fixing breakdown into residues in a couple modified cyclodextrin host PDB/mol2 files.
- **Release 0.2** (Sept. 24, 2019, DOI [10.5281/zenodo.3459975](https://dx.doi.org/10.5281/zenodo.3459975)): Adds host-guest submission template files and instructions; makes more clear which compounds/cases are optional; makes clear that free energy predictions (and uncertainties) are required; enthalpies optional; adds links to [host-guest submission system](http://sampl-submission.us-west-1.elasticbeanstalk.com/submit/)
- **Release 0.3** (Sept. 26, 2019, DOI [10.5281/zenodo.3462865](https://dx.doi.org/10.5281/zenodo.3462865)): Corrected likely charges/protonation states for MGLab23 and MGLab24 in overview table and in jpg and PDF files. Updated corresponding coded and noncoded CDX files. Fixed a mixture of UNK and MGO residue names. Eliminates all instances of atom name HQ which should correspond to a carbon (which for some reason was instead named HX in some hosts, likely causing problems for some workflows). This has been mapped to atom name C9. Reconnects missing bonds in the PDB section of several models. See [PR 42](https://github.com/MobleyLab/SAMPL7/pull/42) for full details. Also removes outdated info in README.md and removes extra guest listed in TrimerTrip submission template.
- **Release 0.4** (Oct. 30, 2019): Adds Isaacs' group TrimerTrip binding data (in `host_guest/analysis/ExperimentalMeasurements`); adds TrimerTrip submissions; adds PHIP2 protein-ligand challenge Stage 1 details.
- **Release 0.4.1** (Nov. 27, 2019, DOI [10.5281/zenodo.3555601](https://dx.doi.org/10.5281/zenodo.3555601)): Fixes and corrects some SMILES formatting errors (see release notes) for protein-ligand challenge, adds host-guest experimental data, adds submission instructions for stage 1 protein-ligand challenge.
- **Relase 0.5** (Aug. 6, 2020, DOI [10.5281/zenodo.3975152](https://dx.doi.org/10.5281/zenodo.3975152)): Adds PHIP2 components from 2019; corrects an OctaAcid value; brings in host-guest challenge results and reference calculations; adds details on SAMPL7 physical property (pKa, logP, logD, PAMPA permeability) challenge along with inputs and submission formats.

### Changes not in a release
- **Finalize physical property format** (Sept. 1, 2020): Update submission formats to include some required fields that had previously been left out (e.g. participant name/organization, and whether submission is ranked). **Changed required format for logP and permeability to better handle molecule ID/choice of tautomer.**
- **Add SAMPL7 physical property submission links** (Sept. 2, 2020)
- Update physical property submission deadline to Oct. 8 (Sept. 28, 2020).
- Update physical property instructions for pKa, logP to clarify (Sept. 30, 2020). Format still the same, but now clarified -- especially for the pKa challenge. We also now highly encourage submission of (optional) logD predictions for the logP challenge.
- **Added additional microstates for pKa challenge**, from Bogdan Iorga (Sept. 30, 2020). Updated instructions to clarify that any states not included in pKa predictions will be assumed to be unpopulated (so participants can omit these states). Updated pKa instructions/template to allow optional submission of macro pKa values.
- **Note that experiments used specified chirality for certain physical property compounds**, `SM35`, `SM36` and `SM37`. So only the structures with specified chirality for these compounds should be used.
- **Add SAMPL7 physical properties experimental values** (Oct. 10, 2020).

## Challenge overview

The SAMPL7 phase of challenges currently includes a physical property challenge on pK<sub>a</sub>, partitioning, and permeability.

Recently concluded SAMPL7 challenges include a protein-ligand component on PHIP2, as well as host-guest binding on three systems: A pair of Gibb Deep Cavity Cavitands (GDCCs), a new "TrimerTrip" molecule from Lyle Isaacs and his group, and a series of cyclodextrin derivatives from Mike Gilson's group. Each host binds one or more guests, and each system involved a total of 9-20 binding free energy calculations.
Additional details are provided below. Several hosts and/or guests were optional.
Note that the [SAMPL8 host-guest challenge is commencing](https://github.com/samplchallenges/SAMPL8)

The planned later stage of SAMPL7 focused on GSK physical property data is being shifted to SAMPL8 because of availability of a more time-sensitive physical property dataset.



### Physical property challenge on pK<sub>a</sub>, partitioning, and permeability

We have a new SAMPL7 challenge focusing on pK<sub>a</sub>, partitioning, and permeability. [The Ballatore group at UCSD](https://pharmacy.ucsd.edu/faculty/ballatore) is contributing a set of measured water-octanol log *P*, log *D*, and pK<sub>a</sub> values for 22 compounds. They also provide PAMPA permeability values they measured.

pK<sub>a</sub> prediction will consist of predicting relative free energies between compound microstates (which could be also thought of as the reaction free energy for that particular microstate transition; [see pKa instructions](https://github.com/samplchallenges/SAMPL7/blob/master/physical_property/pKa/pKa_challenge_instructions.md)). We choose free energies rather than pK<sub>a</sub> values given the recent work of [Gunner et al.](https://link.springer.com/content/pdf/10.1007/s10822-020-00280-7.pdf). For the purposes of the pK<sub>a</sub> challenge all possible tautomers of each ionization (charge) state are defined as distinct protonation microstates. Macro pK<sub>a</sub> values may be submitted to allow for a consistency check.

The partitioning prediction challenge will focus on predicting the difference in free energy for the neutral form between water and octanol. As a part of post prediction analysis challenge oraginzers will combine participant-predicted pK<sub>a</sub> and log *P* values to obtain estimated distribution coefficients, which will also be compared against experimental values. Participants may optionally submit their own log *D* values for a consistency check.

A [PAMPA permeability](https://pubs.acs.org/doi/10.1021/jm060230%2B) prediction challenge will also be run in parallel to the pK<sub>a</sub> and partition coefficient challenge.

All three challenges are optional, so participants may participate in all or any combination of these challenges.

Challenge inputs, submission details and submission templates can be found [here](physical_property/).



### PHIP2 binding prediction

We are excited to announce a new set of SAMPL7 challenges focusing on protein-ligand binding, in partnership with the XChem facility for fragment screening at Diamond Light Source. The second bromodomain of PHIP (PHIP2) was targeted in an extensive X-ray crystallographic fragment screening experiment, leading to the 3D structures of multiple hits. This SAMPL7 challenge will take advantage of this dataset, addressing computational methods for the discrimination of binders from non-binders, binding pose predictions, and the unique opportunity to select new candidate ligands from a database, to be validated experimentally by X-ray crystallography at the Diamond Light Source (Harwell, UK).   

This challenge breaks out into at least three stages on a tight timeline:
1) Identification of binders from fragment screening
2) Prediction of fragment binding modes
3) Selection of new compounds for screening from an experimental database

Stage 3 is now open and focuses selection of possible new binders from a library. See [protein_ligand/README.md](protein_ligand/README.md) for full details.



### Gibb Deep Cavity Cavitand (GDCC) binding of guests

One host-guest series is based on the Gibb Deep Cavity Cavitands (GDCCs), familiar from SAMPL4-6. However, this challenge we swap one of the hosts; previously, we used octa acid (OA) and tetramethyl octa acid (TEMOA); this challenge revisits OA but also utilizes a variant which changes the location of the carboxylates.  Both were developed in the laboratory of Dr. Bruce Gibb (Tulane U), who will provide binding free energies and enthalpies, measured by ITC. In this case the challenge is to predict binding of eight compounds to *exo*-OA (a new host created and studied by the Gibb group and first disclosed in this challenge), and two of these to OA; the other six have been studied previously in OA and can *optionally* be submitted. Existing benchmark datasets based on the OA host may be of interest for those preparing to tackle these new complexes: https://github.com/MobleyLab/benchmarksets; this perpetual review paper also provides a good introduction to the sampling and experimental issues which are known to be relevant in these systems. See the [README on this challenge](host_guest/GDCC_and_guests/README.md) for more details.

### Modified acyclic cucurbituril (TrimerTrip) binding of guests

The Isaacs lab is contributing data on binding of a series of guests to an acyclic cucubituril host, codenamed "TrimerTrip", as detailed in `host_guest/Isaacs_clip`. Guests include compounds which overlap with the GDCC and cyclodextrin-derivative challenges, with a total of roughly 15 complexes being examined. See the [README on this challenge](host_guest/Isaacs_clip/README.md) for more details.

### The cyclodextrin derivatives challenge

The Gilson lab is measuring binding of two guests to ten different hosts, comprising beta-cyclodextrin as well as nine different cyclodextrin derivatives which have a single functional group added at one location around the rim of the cavity. Binding is being characterized via ITC and NMR. The two guest compounds (R-rimantadine and trans-4-methylcyclohexanol) overlap with those used in the TrimerTrip and GDCC challenges. [Full details](host_guest_description.md) are available. Binding to beta-cyclodextrin can optionally be submitted, but literature values for these compounds are available.

## MANIFEST
- [`physical_property`](physical_property): Details on the physical property challenge
- [`host_guest`](host_guest): Details on host-guest challenges
- [`protein_ligand`](protein_ligand): Details on/inputs for PHIP2 bromodomain challenge. Currently Stage 1 is available.
- [`host_guest_description.md`](host_guest_description.md): Detailed description of aspects of the host-guest challenges
- [`protein_ligand_instructions.md`](protein_ligand_instructions.md): Detailed instructions for participation in the protein-ligand challenge.

## SAMPL-related content

If you give a SAMPL-related talk or presentation or an analysis of its data, and are willing to share publicly, please consider posting on Zenodo and linking it to the [SAMPL Zenodo community](https://zenodo.org/communities/sampl?page=1&size=20).

## LICENSE

This material here is made available under CC-BY and MIT licenses, as appropriate:
- MIT for all software/code
- CC-BY 4.0 for all other materials
