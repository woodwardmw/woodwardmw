## Hi, I'm Mark Woodward

Principal AI Engineer at **[SIL Global](https://www.sil.org)**. I work on bringing the AI capabilities that speakers of major languages take for granted (speech recognition, text-to-speech, machine translation and AI assistants) to minority and low-resource language communities.

### What I'm working on now
- **Paratext Translator's Assistant**: an AI assistant for Bible translators, built into [Paratext 10 / Platform.Bible](https://github.com/paranext), plus the server behind it. The server handles provider keys, usage metering and caching, and runs the AI pipelines.
- **[Alpha2](https://multilingualai.com)**: a web app where language teams machine-translate text and generate speech. Its translation engines include Kilele, an in-context-learning LLM translator that drafts from examples retrieved from a team's own texts instead of fine-tuning.
- **AERO**: a REST API for speech in low-resource languages. It covers ASR, forced alignment, voice conversion, denoising, audio infilling and speaker diarization.
- **ASR and TTS**: fine-tuning speech recognition and text-to-speech models for low-resource languages, built on [w2v-BERT-2.0](https://huggingface.co/facebook/w2v-bert-2.0) and [SpeechT5](https://huggingface.co/microsoft/speecht5_tts).
- **Translation quality and checking**: AQuA, our translation quality assessment platform, with LLM-agentic critique and back-translation checking.
- **[Faithbridge](https://ai.sil.org/projects/faithbridge)**: an AI Q&A app that lets local-language translators ask questions by voice or text in 80 languages. Its answers are grounded in curated translation reference resources, with the sources cited.
- **Platform**: serverless GPU inference on [Modal](https://modal.com), training on ClearML, and a shared observability stack (Loki, Prometheus, Tempo).

### Stack
Python, TypeScript · FastAPI, Django, React · PyTorch, Hugging Face Transformers · PostgreSQL · Docker, Modal, ClearML, AWS

### How I work
Methods that generalize: no language-specific rules, so the same approach should work for any of the world's ~7,000 languages.

I'm also interested in how software gets built now. I run a "software factory" style of development, where coding agents work from shared skill libraries such as [Matt Pocock's skills](https://github.com/mattpocock/skills). Specs, test-first implementation, review and CI are largely automated, so a small team can ship like a much larger one.

### Background
- BA Mathematics, Cambridge University
- 10+ years in technical leadership across East Africa before moving into ML
- Based in Poulsbo, WA

### Get in touch
- woodwardmw@gmail.com
