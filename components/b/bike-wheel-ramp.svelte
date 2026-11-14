<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ku-acvbqq"/><path class="gagpxubwp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bike-wheel-ramp" {...props}></Icon>
<style>
:global(.gagpxubwp) {
  d: path("M5.5 15L9 9.25l4.5-1.75l2 3.75m-2-3.75L12.75 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ku-acvbqq) {
  d: path("m2.5 19.5l19-7.5m-19 3a3 3 0 1 0 6 0a3 3 0 1 0-6 0m10-3.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
