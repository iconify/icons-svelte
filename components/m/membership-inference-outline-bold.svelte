<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="knb00ei4h"/><path class="awxqv1b4c"/><path class="ecfyxx_mm"/><path class="vz1f_l41j"/><path class="n3p0zmbop"/><path class="dx5s6zbrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:membership-inference-outline-bold" {...props}></Icon>
<style>
:global(.awxqv1b4c) {
  d: path("M17 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.dx5s6zbrc) {
  d: path("M8 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.ecfyxx_mm) {
  d: path("M5 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.knb00ei4h) {
  d: path("M5 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vz1f_l41j) {
  d: path("M17 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
