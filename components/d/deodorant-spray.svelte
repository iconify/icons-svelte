<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hnet40a7k"/><path class="n5ppr-89k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:deodorant-spray" {...props}></Icon>
<style>
:global(.hnet40a7k) {
  d: path("M5 10a5 3 0 0 1 10 0v10a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 5 20Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n5ppr-89k) {
  d: path("M10 4za1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 10 7a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 10 4m4.5 0L20 2.5m-3 4.25l4.5.5");
}

</style>
