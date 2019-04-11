# homebrew-fortune-clean

An alternate tap of `fortune(6)` that does not install "offensive" content to
your computer.

## Rationale

I don't want hate speech on my hard drive, even lurking in Homebrew's Cellar.

## History

> I admit that I was strongly tempted to simply remove these fortunes, an
> action that I might have justified by pointing to the Notes of the original
> authors. However... I include them, and leave the decision to individual
> system administrators.

— Amy Lewis, 1995

> Anything which assumes as a world view blatantly racist, mysogynist [sic]
> (sexist), or homophobic ideas should not be in either, since they are not
> really funny unless *you* are racist, mysogynist, or homophobic.

— Notes of the original authors, 1993

## Installation

```sh
brew uninstall fortune # if currently installed
brew install zgracem/fortune-clean/fortune # automatically taps this repo
```

## Usage

```sh
fortune -o # results in an error
```

Otherwise, refer to `man fortune` for complete instructions.
