wfa - workflow automatizer - an attempt at an automatizer for tasks in limited size corpora

Apesar de vivermos na era de LLM's, ainda há quem queira ou precise colecionar
documentos de textos para depois processá-los de alguma forma.

Isso envolve:

	- encontrar documentos; 
	- processar seus conteúdos para ter acesso ao texto em si;
	- armazenar os textos;

Este projeto oferece uma maneira de automatizar aspectos da construção de
corpora de até aproximadamente 100,000 sentenças, ou seja, pequenos para scrapers 
profissionais mas grandes demais para serem construídos a mão.

Features:

	- CLI;
	- constrói corpora de portais web;
	- copora são bases de dados sqlite;


Futuro/TODO's:
	- constrói corpora de coleções de documentos pdf;
	- importar como python package no PyPi;
