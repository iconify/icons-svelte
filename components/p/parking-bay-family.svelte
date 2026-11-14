<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u_f-ygbmh"/><path class="rk_ym7bjm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:parking-bay-family" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rk_ym7bjm) {
  d: path("M6 7.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M5 21.5v-4a3.5 3.5 0 0 1 7 0v4m3.25-9a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-.5 9v-2.25a2.25 2.25 0 0 1 4.5 0v2.25");
}

:global(.u_f-ygbmh) {
  d: path("M2 21.5v-19h20v19");
}

</style>
