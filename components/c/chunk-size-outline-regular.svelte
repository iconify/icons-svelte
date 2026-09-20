<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f-g-_s4ku"/><path class="ki-5h0s5c"/><path class="betk_pbkd"/><path class="uwq4cli8g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chunk-size-outline-regular" {...props}></Icon>
<style>
:global(.betk_pbkd) {
  d: path("M8 4 6 6l2 2");
}

:global(.f-g-_s4ku) {
  d: path("M3 13a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.ki-5h0s5c) {
  d: path("M6 6h12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uwq4cli8g) {
  d: path("m16 4 2 2 -2 2");
}

</style>
