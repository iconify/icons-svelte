<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dktry7bqc"/><path class="hqk3lubqo"/><path class="ytbwp-h_h"/><path class="j-jfbgssc"/><path class="btk8fr6ye"/><path class="bo51iypxr"/><path class="e771rwjjh"/><path class="xysie__pz"/><path class="se-pwqb_b"/><path class="km3h1bbzc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cyclone-duotone-thin" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.btk8fr6ye) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 19h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e771rwjjh) {
  d: path("M9 17A5 5 0 0 1 9 7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hqk3lubqo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 17A5 5 0 0 1 9 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j-jfbgssc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.km3h1bbzc) {
  d: path("M15 19h7");
}

:global(.se-pwqb_b) {
  d: path("M2 5h7");
}

:global(.xysie__pz) {
  d: path("M15 7a5 5 0 0 1 0 10");
}

:global(.ytbwp-h_h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 7a5 5 0 0 1 0 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
