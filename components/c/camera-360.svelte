<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7bsc7b6t"/><path class="qtx8rab0b"/><path class="wy3lou_ac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:camera-360" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qtx8rab0b) {
  d: path("M5.5 9.5a6.5 2.25 0 1 0 13 0a6.5 2.25 0 1 0-13 0m-2.5 6q9 7.5 18 0");
}

:global(.r7bsc7b6t) {
  d: path("M5.5 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

:global(.wy3lou_ac) {
  d: path("M18.5 15.5H21V18");
}

</style>
