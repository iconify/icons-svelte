<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><g class="y9tr6bcfx"><circle class="ib21wsbmr"/><path class="be8124b7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:number-9" {...props}></Icon>
<style>
:global(.be8124b7n) {
  d: path("M19.168 30.049c.884 1.156 2.23 1.951 4.46 1.951H24a5.3 5.3 0 0 0 5.3-5.3v-5.4");
}

:global(.ib21wsbmr) {
  cx: 24px;
  cy: 21.3px;
  r: 5.3px;
}

:global(.j3s9ivbxi) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
