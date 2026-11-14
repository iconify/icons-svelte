<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cdycrpb0p"/><path class="qmcvybblw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-draw-circle" {...props}></Icon>
<style>
:global(.cdycrpb0p) {
  d: path("M11.898 19.471L8.5 18.5l-6 2v-15l6-2l7 2l6-2v9.271M8.5 3.5v15m7-13v6.7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qmcvybblw) {
  d: path("M14.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
