<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="uo362vbqt"/><rect class="ploj_obqu"/><rect class="w0q0evbtv"/><path class="r4nmcabkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:car-battery" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ploj_obqu) {
  width: 3.5px;
  height: 2.75px;
  x: 5px;
  y: 4.5px;
  rx: 0.75px;
}

:global(.r4nmcabkd) {
  d: path("M5.25 13.75h3.5M7 12v3.5m8.25-1.75h3.5");
}

:global(.uo362vbqt) {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 7.25px;
  rx: 2px;
}

:global(.w0q0evbtv) {
  width: 3.5px;
  height: 2.75px;
  x: 15.5px;
  y: 4.5px;
  rx: 0.75px;
}

</style>
