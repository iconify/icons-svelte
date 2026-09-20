<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rzt8fd71i"/><path class="vezq7pbcc"/><path class="ymhuvfz3p"/><path class="hxtix3e9b"/><path class="y0y0ccsoe"/><path class="cxgftibra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chemical-reaction-outline-regular" {...props}></Icon>
<style>
:global(.cxgftibra) {
  d: path("m12 10 2 2 -2 2");
}

:global(.hxtix3e9b) {
  d: path("M15 6v11h6V6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rzt8fd71i) {
  d: path("M2 6h8");
}

:global(.vezq7pbcc) {
  d: path("M3 6v11h6V6");
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

:global(.ymhuvfz3p) {
  d: path("M14 6h8");
}

</style>
