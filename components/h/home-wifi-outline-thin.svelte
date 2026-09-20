<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hwufvfb8q"/><path class="a24svzono"/><path class="k_c02d4xz"/><path class="k-jt90-vx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-wifi-outline-thin" {...props}></Icon>
<style>
:global(.a24svzono) {
  d: path("M7 14c3 -3 7 -3 10 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwufvfb8q) {
  d: path("M3 20v-8l9 -9 9 9v8Z");
}

:global(.k_c02d4xz) {
  d: path("M9.5 17c1.5 -1.5 3.5 -1.5 5 0");
}

:global(.k-jt90-vx) {
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
