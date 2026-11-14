<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yz3rs2fes"/><path class="m0a0l-c-p"/><path class="kco5jebxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:inflatable-tent" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kco5jebxt) {
  d: path("m10 17l2-4.5l2 4.5");
}

:global(.m0a0l-c-p) {
  d: path("M6 17c0-6 2.5-10 6-10s6 4 6 10Z");
}

:global(.yz3rs2fes) {
  d: path("M2.5 20c0-10 4-16.5 9.5-16.5S21.5 10 21.5 20Z");
}

</style>
