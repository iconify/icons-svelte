<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ri9l16o0w"/><path class="sj6tq8ckv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:generator-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ri9l16o0w) {
  stroke-opacity: 0.4;
  d: path("M5 7V3h14v4M9 10l-3 3h4l-3 3");
}

:global(.sj6tq8ckv) {
  d: path("M3 7h18v12H3Zm3 12v2m12-2v2m-4-10h3m-3 4h3");
}

</style>
