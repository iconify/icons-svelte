<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hac_zt_2k"/><path class="e325robmt"/><path class="xrit8bb9e"/><path class="ltxni2ncy"/><path class="zjf1fhb5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rater-outline-thin" {...props}></Icon>
<style>
:global(.e325robmt) {
  d: path("M3 13a4 4 0 0 1 8 0");
}

:global(.hac_zt_2k) {
  d: path("M5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ltxni2ncy) {
  d: path("M14 12h7");
}

:global(.xrit8bb9e) {
  d: path("M14 7h7");
}

:global(.zjf1fhb5j) {
  d: path("M14 17h5");
}

</style>
