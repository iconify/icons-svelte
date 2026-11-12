<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gndbq0bkl"/><path class="dpokkjq8r"/><path class="mazoy0feo"/><path class="c9rugwb_d"/><path class="niumi_b1d"/><rect class="pe-_glbxv"/><rect class="sudiajdap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:barcode-line-duotone" {...props}></Icon>
<style>
:global(.c9rugwb_d) {
  stroke-linecap: round;
  d: path("M22 18.978L22 4.97803");
}

:global(.dpokkjq8r) {
  stroke-linecap: round;
  d: path("M5.53906 18.9785L5.53906 4.97852");
}

:global(.gndbq0bkl) {
  stroke-linecap: round;
  d: path("M12.3164 18.9785L12.3164 4.97852");
}

:global(.jx0p4fbya) {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mazoy0feo) {
  stroke-linecap: round;
  d: path("M15.2217 18.9785L15.2217 4.97852");
}

:global(.niumi_b1d) {
  stroke-linecap: round;
  d: path("M2.63379 18.9785L2.63379 4.97852");
}

:global(.pe-_glbxv) {
  width: 0.968px;
  height: 14.043px;
  x: 8.443px;
  y: 4.957px;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 0.484px;
}

:global(.sudiajdap) {
  width: 0.968px;
  height: 14.043px;
  x: 18.127px;
  y: 4.935px;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 0.484px;
}

</style>
