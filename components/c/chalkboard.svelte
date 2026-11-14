<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q1to8jb7j"/><path class="g7wrg1b7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chalkboard" {...props}></Icon>
<style>
:global(.g7wrg1b7s) {
  d: path("M6.5 8C8 6 9.5 9 11 7c1.5-1.5 3 1 6.5-.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q1to8jb7j) {
  d: path("M5.125 3.5h13.75A2.625 2.625 0 0 1 21.5 6.125v7.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 13.875v-7.75A2.625 2.625 0 0 1 5.125 3.5M7 16.5L5 21m12-4.5l2 4.5");
}

</style>
