<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sur-qkf7m"/><path class="z9ittvbis"/><path class="jl5_x8rdu"/><path class="fnwx1d-uu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:blue-hour-outline-regular" {...props}></Icon>
<style>
:global(.fnwx1d-uu) {
  d: path("m17 9.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
}

:global(.jl5_x8rdu) {
  d: path("m7 5 3 3 -3 3 -3 -3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sur-qkf7m) {
  d: path("M7 21a5 5 0 0 1 10 0");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
