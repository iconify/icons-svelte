<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eohvp-yvr"/><path class="dw0f580hj"/><path class="ll460g7hf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ranch-house" {...props}></Icon>
<style>
:global(.dw0f580hj) {
  d: path("M4.5 10.5V20h15v-9.5M2.5 20h19");
}

:global(.eohvp-yvr) {
  d: path("M2.5 11.5L12 6l9.5 5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ll460g7hf) {
  d: path("M7.25 20v-5.5H10V20m4.25-6.5h1.25A1.5 1.5 0 0 1 17 15a1.5 1.5 0 0 1-1.5 1.5h-1.25a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
