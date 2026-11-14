<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xi65ahb3q"/><path class="e1x0z0tob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ad-label-sponsored" {...props}></Icon>
<style>
:global(.e1x0z0tob) {
  d: path("M17 9.25C16.75 8.5 15.75 8 14.5 8C13 8 12 8.75 12 10c0 2.5 5 1.5 5 4c0 1.25-1 2-2.5 2s-2.5-.5-2.75-1.25m2.75-8V8m0 8v1.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xi65ahb3q) {
  d: path("M2.5 12L8 4h11.5q2 0 2 2v12q0 2-2 2H8Z");
}

</style>
