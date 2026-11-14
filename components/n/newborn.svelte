<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eaj606bzg"/><path class="cg8wkn4ku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:newborn" {...props}></Icon>
<style>
:global(.cg8wkn4ku) {
  d: path("M7.25 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0M8 14.5c2.5-.5 5.75.5 7.75 2.5");
}

:global(.eaj606bzg) {
  d: path("M16.015 3.39za6.5 6.5 0 0 1 3.144 8.638l-2.536 5.438a6.5 6.5 0 0 1-8.638 3.144a6.5 6.5 0 0 1-3.144-8.638l2.536-5.438a6.5 6.5 0 0 1 8.638-3.144");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
