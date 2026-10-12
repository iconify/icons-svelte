<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="phjvadcnz"/><path class="xb-_hll7y"/><circle class="ozmcgbndl"/><path class="nwgaeub8v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:profile-card" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nwgaeub8v) {
  d: path("M13 12.75h4.5M6 16.5h12");
}

:global(.ozmcgbndl) {
  cx: 8px;
  cy: 10.25px;
  r: 3px;
}

:global(.phjvadcnz) {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 3px;
}

:global(.xb-_hll7y) {
  d: path("M12.5 9.5h8.75");
}

</style>
