<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pjhvei21y"/><path class="d8uezydnt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:quota-progress" {...props}></Icon>
<style>
:global(.d8uezydnt) {
  fill: currentColor;
  d: path("M6.5 10H13a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 13 14H6.5A1.5 1.5 0 0 1 5 12.5v-1A1.5 1.5 0 0 1 6.5 10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pjhvei21y) {
  d: path("M5.125 7.5h13.75a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 13.875v-3.75A2.625 2.625 0 0 1 5.125 7.5");
}

</style>
