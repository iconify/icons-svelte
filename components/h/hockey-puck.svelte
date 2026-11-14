<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ri9trlm_k"/><path class="nvy0qd86y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hockey-puck" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nvy0qd86y) {
  d: path("M3.5 10v4c0 2.5 3.75 4.5 8.5 4.5s8.5-2 8.5-4.5v-4");
}

:global(.ri9trlm_k) {
  d: path("M3.5 10a8.5 3.5 0 1 0 17 0a8.5 3.5 0 1 0-17 0");
}

</style>
