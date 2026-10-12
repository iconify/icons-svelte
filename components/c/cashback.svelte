<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="drbi0rnnl"/><path class="rjtfrzb-f"/><circle class="qy4e2ebar"/><circle class="peiq2hfxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cashback" {...props}></Icon>
<style>
:global(.drbi0rnnl) {
  d: path("M3.75 12a8.25 8.25 0 1 0 2.42-5.83L3.75 8.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.peiq2hfxm) {
  cx: 12px;
  cy: 12px;
  r: 1.75px;
}

:global(.qy4e2ebar) {
  cx: 12px;
  cy: 12px;
  r: 4.25px;
}

:global(.rjtfrzb-f) {
  d: path("M3.75 3.75v4.5h4.5");
}

</style>
