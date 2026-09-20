<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uohzictri"/><path class="anx8jnbhv"/><path class="zddikdsez"/><path class="emo-jf0pj"/><path class="teggaxbsd"/><path class="oifr9zbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:birdwatching-duotone-regular" {...props}></Icon>
<style>
:global(.anx8jnbhv) {
  fill: currentColor;
  d: path("M6 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.emo-jf0pj) {
  d: path("M6 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.teggaxbsd) {
  d: path("M8 16v4");
}

:global(.uohzictri) {
  fill: currentColor;
  d: path("M8 16c-3 0 -5 -3 -5 -6s2 -5 5 -5 5 2 5 5l4 -4v8c-2 -1 -3 -2 -4 -3 -1 3 -3 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zddikdsez) {
  d: path("M8 16c-3 0 -5 -3 -5 -6s2 -5 5 -5 5 2 5 5l4 -4v8c-2 -1 -3 -2 -4 -3 -1 3 -3 5 -5 5");
}

</style>
