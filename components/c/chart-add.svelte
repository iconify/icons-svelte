<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bwvsz2b2k"/><path class="lcyk3hb9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-add" {...props}></Icon>
<style>
:global(.bwvsz2b2k) {
  d: path("M3.5 3v17.5h9.8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lcyk3hb9o) {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m-1 10v7M14.5 18h7");
}

</style>
