<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a4f92acjz"/><path class="pyjtflbpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mouse-duocolor-round" {...props}></Icon>
<style>
:global(.a4f92acjz) {
  stroke-opacity: 0.4;
  d: path("M12 7v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pyjtflbpf) {
  d: path("M6 9a6 6 0 1 1 12 0v6a6 6 0 1 1-12 0Z");
}

</style>
