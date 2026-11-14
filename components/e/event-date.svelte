<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vgyc0z28i"/><path class="n_mjdibzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:event-date" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n_mjdibzt) {
  d: path("M14.25 13h1.5a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 15.75 18h-1.5a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 14.25 13");
}

:global(.vgyc0z28i) {
  d: path("M7.375 4.5h9.25A4.375 4.375 0 0 1 21 8.875v8.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-8.25A4.375 4.375 0 0 1 7.375 4.5M3 9.5h18m-13-7v4m8-4v4");
}

</style>
