<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dfcfuobnq"/><circle class="c2vbuccni"/><path class="hdj66lbws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mri-scanner" {...props}></Icon>
<style>
:global(.c2vbuccni) {
  cx: 12px;
  cy: 10.5px;
  r: 3.5px;
}

:global(.dfcfuobnq) {
  width: 18.5px;
  height: 15px;
  x: 2.75px;
  y: 3px;
  rx: 3px;
}

:global(.hdj66lbws) {
  d: path("M6 21.25h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
