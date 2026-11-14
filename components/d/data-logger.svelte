<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eprg0dg7m"/><path class="t-e85zbku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:data-logger" {...props}></Icon>
<style>
:global(.eprg0dg7m) {
  d: path("M6 4h6a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 12 16H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 4m9.5 6H17a2 2 0 0 1 2 2v3m0 0za1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-3.5A1.5 1.5 0 0 1 19 15");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t-e85zbku) {
  d: path("M5.75 13H8.5v-3H11V7h1.5");
}

</style>
