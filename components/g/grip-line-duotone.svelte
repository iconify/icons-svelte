<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="ucr1abtlg"/><circle class="msuzhccpk"/><circle class="rf2iq2_-s"/><circle class="b0x94kb-u"/><circle class="wply1zb2x"/><circle class="ne3znqnan"/><circle class="ofiabdbkw"/><circle class="c0odglb-w"/><circle class="vy0kz1bbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grip-line-duotone" {...props}></Icon>
<style>
:global(.b0x94kb-u) {
  cx: 5.008px;
  cy: 19px;
  r: 0.75px;
}

:global(.c0odglb-w) {
  cx: 19.008px;
  cy: 12px;
  r: 0.75px;
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.msuzhccpk) {
  cx: 12.016px;
  cy: 12px;
  r: 0.75px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ne3znqnan) {
  cx: 4.992px;
  cy: 5px;
  r: 0.75px;
}

:global(.ofiabdbkw) {
  cx: 19.008px;
  cy: 19px;
  r: 0.75px;
}

:global(.rf2iq2_-s) {
  cx: 12px;
  cy: 5px;
  r: 0.75px;
}

:global(.ucr1abtlg) {
  cx: 12.016px;
  cy: 19px;
  r: 0.75px;
}

:global(.vy0kz1bbg) {
  cx: 18.992px;
  cy: 5px;
  r: 0.75px;
}

:global(.wply1zb2x) {
  cx: 5.008px;
  cy: 12px;
  r: 0.75px;
}

</style>
