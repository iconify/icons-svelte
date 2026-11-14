<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xdtenrd_u"/><path class="b3_fxlb3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:glass-pipe-bend" {...props}></Icon>
<style>
:global(.b3_fxlb3q) {
  d: path("M10 2.5L8.5 4v10a3.5 3.5 0 0 0 7 0V4L14 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xdtenrd_u) {
  d: path("M3.5 2.5L5 4v10a7 7 0 0 0 14 0V4l1.5-1.5");
}

</style>
