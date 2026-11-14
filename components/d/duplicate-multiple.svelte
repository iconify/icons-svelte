<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1m2hsyzk"/><path class="pbqudibor"/><path class="dv344qf1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:duplicate-multiple" {...props}></Icon>
<style>
:global(.dv344qf1f) {
  d: path("M3.5 13.5v-8a2 2 0 0 1 2-2h8");
}

:global(.g1m2hsyzk) {
  d: path("M13.5 10H17a3.5 3.5 0 0 1 3.5 3.5V17a3.5 3.5 0 0 1-3.5 3.5h-3.5A3.5 3.5 0 0 1 10 17v-3.5a3.5 3.5 0 0 1 3.5-3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pbqudibor) {
  d: path("M6.75 17V8.75a2 2 0 0 1 2-2H17");
}

</style>
