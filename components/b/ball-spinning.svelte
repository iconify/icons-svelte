<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwrftd82o"/><path class="v3yg5zbbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ball-spinning" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nwrftd82o) {
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0");
}

:global(.v3yg5zbbs) {
  d: path("M8.5 6.5q2.5 5.5 0 11m7-11q-2.5 5.5 0 11m-6.749 3.427A9.5 9.5 0 0 1 3.073 8.751m12.176-5.678a9.5 9.5 0 0 1 5.678 12.176");
}

</style>
