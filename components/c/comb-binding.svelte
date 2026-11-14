<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z6hgrju_h"/><path class="x3hh9odwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:comb-binding" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x3hh9odwt) {
  d: path("M7.25 2.5zA1.25 1.25 0 0 1 8.5 3.75v2.5A1.25 1.25 0 0 1 7.25 7.5A1.25 1.25 0 0 1 6 6.25v-2.5A1.25 1.25 0 0 1 7.25 2.5m4.75 0za1.25 1.25 0 0 1 1.25 1.25v2.5A1.25 1.25 0 0 1 12 7.5a1.25 1.25 0 0 1-1.25-1.25v-2.5A1.25 1.25 0 0 1 12 2.5m4.75 0zA1.25 1.25 0 0 1 18 3.75v2.5a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25v-2.5a1.25 1.25 0 0 1 1.25-1.25");
}

:global(.z6hgrju_h) {
  d: path("M8 4.5h8A3.5 3.5 0 0 1 19.5 8v7.5A3.5 3.5 0 0 1 16 19H8a3.5 3.5 0 0 1-3.5-3.5V8A3.5 3.5 0 0 1 8 4.5m-1.5 17h11");
}

</style>
