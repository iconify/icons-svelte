<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8u760b4u"/><path class="k0ws3dbdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dependent-variable" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k0ws3dbdm) {
  d: path("M6.5 17.5a9 9 0 0 0 2.586-.697m7.031-6.426C17.223 8.843 18.345 7.053 19.5 5M11 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.p8u760b4u) {
  d: path("M3.5 3v17.5H21");
}

</style>
