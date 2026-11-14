<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="pjqfph8iv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cable-cross-section" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

:global(.pjqfph8iv) {
  d: path("M10 7.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0m3.75 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
