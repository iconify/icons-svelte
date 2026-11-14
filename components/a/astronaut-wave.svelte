<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rvx706b4v"/><path class="rs0b3lb4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:astronaut-wave" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rs0b3lb4m) {
  d: path("M9 6.25h2a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H9a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 6.25");
}

:global(.rvx706b4v) {
  d: path("M4.75 7.75a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0M3 21.5c0-3.5 3-5.75 7-5.75s7 2.25 7 5.75m-1.5-4l4.5-12");
}

</style>
