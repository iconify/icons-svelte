<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jtchsjxso"/><path class="i-e6e76co"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:convention-center" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i-e6e76co) {
  d: path("M7 19v-8.5h10V19m-6.75-8.5V19m3.5-8.5V19");
}

:global(.jtchsjxso) {
  d: path("M4 4.5h16A1.5 1.5 0 0 1 21.5 6A1.5 1.5 0 0 1 20 7.5H4A1.5 1.5 0 0 1 2.5 6A1.5 1.5 0 0 1 4 4.5m0 3V19h16V7.5");
}

</style>
