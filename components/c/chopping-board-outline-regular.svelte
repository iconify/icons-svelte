<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jxalr7p_q"/><path class="jkajs8zlu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chopping-board-outline-regular" {...props}></Icon>
<style>
:global(.jkajs8zlu) {
  d: path("M13 8V4h4v4");
}

:global(.jxalr7p_q) {
  d: path("M3 8v12h14V8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
