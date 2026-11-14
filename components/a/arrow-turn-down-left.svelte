<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i697pwblp"/><path class="c486jtb9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arrow-turn-down-left" {...props}></Icon>
<style>
:global(.c486jtb9l) {
  d: path("m3.5 15l4 4l4-4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i697pwblp) {
  d: path("M20.5 5h-8a5 5 0 0 0-5 5v9");
}

</style>
