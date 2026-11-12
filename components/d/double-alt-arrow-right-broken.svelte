<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zjnva_byo"/><path class="ggrp1gbkp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-right-broken" {...props}></Icon>
<style>
:global(.ggrp1gbkp) {
  d: path("M7 5L13 12L11.5 13.75M7 19L9 16.6667");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zjnva_byo) {
  d: path("M11 19L17 12L15.5 10.25M11 5L13 7.33333");
}

</style>
