<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="icydrxplj"/><path class="q-6prybqy"/><rect class="mr0ir1bhl"/><path class="ze7l-fbjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:order-picking" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.icydrxplj) {
  width: 10.5px;
  height: 15.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.mr0ir1bhl) {
  width: 5.75px;
  height: 8.75px;
  x: 15.5px;
  y: 12.5px;
  rx: 1.25px;
}

:global(.q-6prybqy) {
  d: path("M5.75 6.75h5m-5 3.25h5m-5 3.25h2.5");
}

:global(.ze7l-fbjh) {
  d: path("M18.38 12.5v3");
}

</style>
