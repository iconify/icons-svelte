<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yx5zm_bhq"/><circle class="s7r9jey2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chart-axis" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s7r9jey2r) {
  cx: 13.5px;
  cy: 10.25px;
  r: 1.5px;
}

:global(.yx5zm_bhq) {
  d: path("M5.75 2.75v13.5a2 2 0 0 0 2 2h13.5M3.5 5l2.25-2.25L8 5m11 11l2.25 2.25L19 20.5m-8.25-2.25v3m5-3v3m-13-12.5h3m-3 4.5h3");
}

</style>
