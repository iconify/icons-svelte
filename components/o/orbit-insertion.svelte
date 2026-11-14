<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iepfipbmk"/><path class="qxz3rvbvy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:orbit-insertion" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iepfipbmk) {
  d: path("M5.5 11a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

:global(.qxz3rvbvy) {
  d: path("M3 21c1.5-3 2.5-6 2.5-10m-2.25 2.25L5.5 11l2.25 2.25M10.5 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
