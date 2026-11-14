<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d2kfgabxw"/><path class="i3scrsbcw"/><path class="i5lcxlbmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:endoscopy" {...props}></Icon>
<style>
:global(.d2kfgabxw) {
  d: path("M11 7.5c2-1.5 8.5-1.5 8.5 5c0 5-4 8-8.5 8c-4 0-6.5-2.5-6.5-5.5c0-1.5 1-2.5 2.5-2.5c2 0 2-2.5 2-3.5Zm-1.5-5v6.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i3scrsbcw) {
  d: path("M12.5 2.5v7c0 1.5 1 2.75 2.5 3.25");
}

:global(.i5lcxlbmo) {
  fill: currentColor;
  d: path("M14.5 13a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
