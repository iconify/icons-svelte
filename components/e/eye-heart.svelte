<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="znff25bsj"/><path class="ywt52j5ec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:eye-heart" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ywt52j5ec) {
  d: path("M7.25 9.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M18 21s-3-1.9-3-4c0-1.1.8-2 1.75-2c.55 0 1 .25 1.25.75c.25-.5.7-.75 1.25-.75c.95 0 1.75.9 1.75 2c0 2.1-3 4-3 4");
}

:global(.znff25bsj) {
  d: path("M2.5 9.75C4 6.5 6.6 4.5 9.75 4.5s5.75 2 7.25 5.25C15.5 13 12.9 15 9.75 15S4 13 2.5 9.75");
}

</style>
