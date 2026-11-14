<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hnrefib5r"/><path class="nmdu7wxtz"/><path class="jyzkirbsd"/><path class="mfddg1bee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:casino" {...props}></Icon>
<style>
:global(.hnrefib5r) {
  d: path("M3.5 7a8.5 4.5 0 1 0 17 0a8.5 4.5 0 1 0-17 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jyzkirbsd) {
  d: path("M3.5 11a8.5 4.5 0 0 0 17 0");
}

:global(.mfddg1bee) {
  d: path("M3.5 14a8.5 4.5 0 0 0 17 0M8 7a4 1.75 0 1 0 8 0a4 1.75 0 1 0-8 0");
}

:global(.nmdu7wxtz) {
  d: path("M3.5 7v10a8.5 4.5 0 0 0 17 0V7");
}

</style>
