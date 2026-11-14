<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e64-71crn"/><path class="keajmbcfy"/><path class="a7bo6jbho"/><path class="uotnk01or"/><path class="zfk1a0bxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:card-expiry-input" {...props}></Icon>
<style>
:global(.a7bo6jbho) {
  d: path("m9 15l2.5-6");
}

:global(.e64-71crn) {
  d: path("M4.625 6h14.75A2.625 2.625 0 0 1 22 8.625v6.75A2.625 2.625 0 0 1 19.375 18H4.625A2.625 2.625 0 0 1 2 15.375v-6.75A2.625 2.625 0 0 1 4.625 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.keajmbcfy) {
  fill: currentColor;
  d: path("M5.125 12.75h2.25a.625.625 0 0 1 .625.625a.625.625 0 0 1-.625.625h-2.25a.625.625 0 0 1-.625-.625a.625.625 0 0 1 .625-.625");
}

:global(.uotnk01or) {
  fill: currentColor;
  d: path("M13.375 12.75h2.25a.625.625 0 0 1 .625.625a.625.625 0 0 1-.625.625h-2.25a.625.625 0 0 1-.625-.625a.625.625 0 0 1 .625-.625");
}

:global(.zfk1a0bxg) {
  d: path("M19.25 9v6");
}

</style>
