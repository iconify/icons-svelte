<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q0_gb6qzx"/><path class="b4yhy9bzz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fuel-card" {...props}></Icon>
<style>
:global(.b4yhy9bzz) {
  d: path("M2.75 9.25h18.5M6 14.75h5M17 11c1.2 1.4 1.75 2.3 1.75 3.1a1.75 1.75 0 0 1-3.5 0c0-.8.55-1.7 1.75-3.1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q0_gb6qzx) {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2px;
}

</style>
