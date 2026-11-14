<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wst7c_x3t"/><path class="kixeaabee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:image-square" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kixeaabee) {
  d: path("M3.5 16.5L9 11l5.5 5.5l2-2l4 4m-6.75-10a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.wst7c_x3t) {
  d: path("M7.875 3.5h8.25A4.375 4.375 0 0 1 20.5 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-8.25A4.375 4.375 0 0 1 3.5 16.125v-8.25A4.375 4.375 0 0 1 7.875 3.5");
}

</style>
