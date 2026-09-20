<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e1i8cybef"/><path class="jxalr7p_q"/><path class="jkajs8zlu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chopping-board-duotone-thin" {...props}></Icon>
<style>
:global(.e1i8cybef) {
  fill: currentColor;
  d: path("M3 8v12h14V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jkajs8zlu) {
  d: path("M13 8V4h4v4");
}

:global(.jxalr7p_q) {
  d: path("M3 8v12h14V8Z");
}

</style>
