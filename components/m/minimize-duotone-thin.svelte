<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e9pla1bcq"/><path class="n7st3f6hi"/><path class="ch2v2wvap"/><path class="q6ka8bllw"/><path class="gsqbmignj"/><path class="dpjjh6qnb"/><path class="ya5oksyke"/><path class="uiel3fblr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:minimize-duotone-thin" {...props}></Icon>
<style>
:global(.ch2v2wvap) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 15h-6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dpjjh6qnb) {
  d: path("M15 3v6h6");
}

:global(.e9pla1bcq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3v6H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gsqbmignj) {
  d: path("M9 3v6H3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n7st3f6hi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 3v6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q6ka8bllw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 21v-6H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uiel3fblr) {
  d: path("M9 21v-6H3");
}

:global(.ya5oksyke) {
  d: path("M21 15h-6v6");
}

</style>
