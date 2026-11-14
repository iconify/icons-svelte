<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qelbh0-8f"/><path class="tp2slzvae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:aquarium-visit" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qelbh0-8f) {
  d: path("M2.5 4.5v13a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2v-13m-19 2h19");
}

:global(.tp2slzvae) {
  d: path("M6 12c2-3.5 6.5-3.5 8.5 0l3-2.5v5l-3-2.5c-2 3.5-6.5 3.5-8.5 0m3 0h.01");
}

</style>
