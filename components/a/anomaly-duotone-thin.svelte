<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hogx-wb3c"/><path class="bp-bj-6is"/><path class="pmt-nxb9a"/><path class="rkhcgsbdl"/><path class="l23it1b0d"/><path class="t164-vbgd"/><path class="n92hyrp1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:anomaly-duotone-thin" {...props}></Icon>
<style>
:global(.bp-bj-6is) {
  fill: currentColor;
  d: path("M16 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hogx-wb3c) {
  fill: currentColor;
  d: path("M6 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.l23it1b0d) {
  d: path("M6 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n92hyrp1a) {
  d: path("M9 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.pmt-nxb9a) {
  fill: currentColor;
  d: path("M9 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.t164-vbgd) {
  d: path("M16 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
