<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t1n1s_mtk"/><path class="e3tmhtu7v"/><path class="nce43obfj"/><path class="mzs8isbdn"/><path class="vo7q96bds"/><path class="ilryez4rq"/><path class="qi3wr9i3q"/><path class="m3p-trbfr"/><path class="uvtjmqbif"/><path class="o58i3acrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chord-duotone-thin" {...props}></Icon>
<style>
:global(.e3tmhtu7v) {
  fill: currentColor;
  d: path("M8 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ilryez4rq) {
  d: path("M8 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.m3p-trbfr) {
  d: path("M8 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.mzs8isbdn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 18V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nce43obfj) {
  fill: currentColor;
  d: path("M8 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.o58i3acrw) {
  d: path("M12 4h5");
}

:global(.qi3wr9i3q) {
  d: path("M8 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.t1n1s_mtk) {
  fill: currentColor;
  d: path("M8 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uvtjmqbif) {
  d: path("M12 18V4");
}

:global(.vo7q96bds) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
