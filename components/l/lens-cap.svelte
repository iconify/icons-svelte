<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="m5xhbpbfp"/><rect class="va5xsmb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lens-cap" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m5xhbpbfp) {
  d: path("M6.5 9.25v5.5m11-5.5v5.5");
}

:global(.va5xsmb9x) {
  width: 5px;
  height: 2.5px;
  x: 9.5px;
  y: 10.75px;
  rx: 1.25px;
}

</style>
