<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="it8gv7b4j"/><path class="rm2dge7vs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-embed" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.it8gv7b4j) {
  d: path("M12.09 19.526L8.5 18.5l-6 2v-15l6-2l7 2l6-2v9.571M8.5 3.5v15m7-13v6.7");
}

:global(.rm2dge7vs) {
  d: path("m16 15l-2 2.5l2 2.5m3.5-5l2 2.5l-2 2.5");
}

</style>
