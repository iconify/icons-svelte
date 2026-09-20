<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oh4p-ccfe"/><path class="vh0_rdbqi"/><path class="t8z7o_gvd"/><path class="aalbzcb_j"/><path class="vslz5yb3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:jumbo-frame-outline-regular" {...props}></Icon>
<style>
:global(.aalbzcb_j) {
  d: path("M2 5.5h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oh4p-ccfe) {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.t8z7o_gvd) {
  d: path("M22 4v3");
}

:global(.vh0_rdbqi) {
  d: path("M2 4v3");
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

</style>
