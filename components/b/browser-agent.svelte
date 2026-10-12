<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="hufrlzpcu"/><path class="pxdjhw_3y"/><path class="v_h_ylb4t"/><path class="vzolxrb_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:browser-agent" {...props}></Icon>
<style>
:global(.hufrlzpcu) {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.pxdjhw_3y) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.25h18.5");
}

:global(.v_h_ylb4t) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 6h.01");
}

:global(.vzolxrb_o) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10.5q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
