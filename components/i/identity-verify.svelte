<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jh8sg_bol"/><circle class="j19le_uky"/><path class="sjadambmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:identity-verify" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j19le_uky) {
  cx: 8px;
  cy: 10.25px;
  r: 2px;
}

:global(.jh8sg_bol) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 2px;
}

:global(.sjadambmn) {
  d: path("M4.75 18.25a3.25 3.25 0 0 1 6.5 0M14 13.5l1.75 1.75l3.25-3.5");
}

</style>
