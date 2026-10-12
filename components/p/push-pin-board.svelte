<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zyt56mbrm"/><path class="t1ruryb_u"/><circle class="ix5kygeym"/><circle class="htd5wpb8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:push-pin-board" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.htd5wpb8c) {
  cx: 16px;
  cy: 11px;
  r: 1.5px;
}

:global(.ix5kygeym) {
  cx: 8px;
  cy: 8.5px;
  r: 1.5px;
}

:global(.t1ruryb_u) {
  d: path("M6.5 8.5H5.25v8.25h5.5V8.5H9.5m5.25 2.5h-1.5v6.25h5.5V11H17.5");
}

:global(.zyt56mbrm) {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2px;
}

</style>
