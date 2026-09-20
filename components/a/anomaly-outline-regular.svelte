<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rkhcgsbdl"/><path class="l23it1b0d"/><path class="t164-vbgd"/><path class="n92hyrp1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:anomaly-outline-regular" {...props}></Icon>
<style>
:global(.l23it1b0d) {
  d: path("M6 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n92hyrp1a) {
  d: path("M9 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.t164-vbgd) {
  d: path("M16 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
