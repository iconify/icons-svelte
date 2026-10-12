<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q0_gb6qzx"/><path class="v1gjv4oug"/><rect class="tjy3rxbwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rfid-tag" {...props}></Icon>
<style>
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

:global(.tjy3rxbwv) {
  width: 3.5px;
  height: 3px;
  x: 10.25px;
  y: 10.5px;
  rx: 0.5px;
}

:global(.v1gjv4oug) {
  d: path("M7 8.25h10a1 1 0 0 1 1 1v5.5a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-5.5a1 1 0 0 1 1-1");
}

</style>
