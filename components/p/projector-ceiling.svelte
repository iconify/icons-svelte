<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="en-x_ccpr"/><path class="rzk53tbgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:projector-ceiling" {...props}></Icon>
<style>
:global(.en-x_ccpr) {
  d: path("M8.5 8.5h7A3.5 3.5 0 0 1 19 12a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 12a3.5 3.5 0 0 1 3.5-3.5m3.5-6v6m-4-6h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rzk53tbgq) {
  d: path("M13.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M10 19l-3 2m7-2l3 2");
}

</style>
