<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="voeieob5r"/><path class="g9va-mb5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plug-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.g9va-mb5c) {
  d: path("M6 16V7h9m3 3v7h-7m1 0v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.voeieob5r) {
  stroke-opacity: 0.4;
  d: path("M9 3v4m6-4v4M2 20L20 2");
}

</style>
