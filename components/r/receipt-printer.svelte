<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fyw-a1b9g"/><rect class="vmlufcc6h"/><path class="vdgh-dbtb"/><path class="l5fw6da3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:receipt-printer" {...props}></Icon>
<style>
:global(.fyw-a1b9g) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 10.75v-7.5l1.75 1l1.75-1l1.75 1l1.75-1l1.75 1l1.75-1v7.5m-8-3.25h5.5");
}

:global(.l5fw6da3f) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 16h.01");
}

:global(.vdgh-dbtb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 16h6");
}

:global(.vmlufcc6h) {
  width: 18.5px;
  height: 10.5px;
  x: 2.75px;
  y: 10.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
