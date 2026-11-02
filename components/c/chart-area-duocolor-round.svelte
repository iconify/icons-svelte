<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zyqlyotss"/><path class="cmls3oiey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-area-duocolor-round" {...props}></Icon>
<style>
:global(.cmls3oiey) {
  d: path("M7 14v-1c0-.64.36-1.36 1-2l1-1a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 0 2 0l4-4c.369-.369 1 .262 1 1v6a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zyqlyotss) {
  stroke-opacity: 0.4;
  d: path("M3 4v12a4 4 0 0 0 4 4h14");
}

</style>
