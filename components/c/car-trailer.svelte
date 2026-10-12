<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="s1qubm6cb"/><path class="x5mr4b4bl"/><circle class="n68tfnh1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:car-trailer" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n68tfnh1s) {
  cx: 9.25px;
  cy: 17.75px;
  r: 2.75px;
}

:global(.s1qubm6cb) {
  width: 13px;
  height: 9px;
  x: 2.75px;
  y: 8.75px;
  rx: 1.5px;
}

:global(.x5mr4b4bl) {
  d: path("M2.75 11.75h13m0 2.5h5.5m-2 0v4m-1 0h2");
}

</style>
