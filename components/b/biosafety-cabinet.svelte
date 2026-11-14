<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l-_d3abuw"/><path class="ohqwhib9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:biosafety-cabinet" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l-_d3abuw) {
  d: path("M6.5 3h11A3.5 3.5 0 0 1 21 6.5v8a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 14.5v-8A3.5 3.5 0 0 1 6.5 3m-1 15v3.5m13-3.5v3.5M3 8.5h18m-9 2.75v4");
}

:global(.ohqwhib9c) {
  d: path("M9.75 13L12 15.25L14.25 13");
}

</style>
