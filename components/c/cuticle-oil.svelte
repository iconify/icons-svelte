<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q_u15bp5j"/><path class="ie6aejbji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cuticle-oil" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ie6aejbji) {
  d: path("M8.25 11V8.75a3.75 3.75 0 0 1 7.5 0V11q-3.75 1.5-7.5 0");
}

:global(.q_u15bp5j) {
  d: path("M5.5 13V8.75a6.5 6.5 0 0 1 13 0V13M12 15.25c1.5 1.5 3 2.75 3 3.75a3 3 0 0 1-6 0c0-1 1.5-2.25 3-3.75");
}

</style>
