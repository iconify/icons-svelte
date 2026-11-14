<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ijq7_cbts"/><path class="sxc00sb0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:genre-adventure" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ijq7_cbts) {
  d: path("M3.5 12a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0");
}

:global(.sxc00sb0d) {
  d: path("m14.74 10.851l-.912 2.174a1.5 1.5 0 0 1-.803.803l-2.174.912a1.215 1.215 0 0 1-1.591-1.591l.912-2.174a1.5 1.5 0 0 1 .803-.803l2.174-.912a1.215 1.215 0 0 1 1.591 1.591M12 2.5v1m0 17v1M2.5 12h1m17 0h1");
}

</style>
