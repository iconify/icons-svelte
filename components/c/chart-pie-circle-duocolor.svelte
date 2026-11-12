<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xjoen_btq"/><path class="po4qkkwyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-pie-circle-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.po4qkkwyb) {
  d: path("M21 12a9 9 0 1 0-9 9v-9z");
}

:global(.xjoen_btq) {
  stroke-opacity: 0.4;
  d: path("M15 18a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
