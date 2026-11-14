<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z73ri-cxq"/><path class="kjwcs4b9n"/><path class="bcwxzk24p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hotspot" {...props}></Icon>
<style>
:global(.bcwxzk24p) {
  fill: currentColor;
  d: path("M10.25 16.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kjwcs4b9n) {
  d: path("M2.603 13.08a10 10 0 0 1 18.794 0");
}

:global(.z73ri-cxq) {
  d: path("M7.302 14.79a5 5 0 0 1 9.396 0");
}

</style>
