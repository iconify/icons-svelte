<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o4b5bv6se"/><path class="zugrvnb7t"/><path class="o2uaggb1q"/><path class="p4jzd4blg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:car-front-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o2uaggb1q) {
  d: path("M5 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.o4b5bv6se) {
  d: path("M2 19v-6l6 -6h8l6 6v6Z");
}

:global(.p4jzd4blg) {
  d: path("M17 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zugrvnb7t) {
  d: path("M2 13h20");
}

</style>
