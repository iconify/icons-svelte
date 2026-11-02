<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zq7hq1-vu"/><path class="yondeb0iz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bell-dot-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yondeb0iz) {
  d: path("M19 13zc0 1 1 1 1 2a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2c0-1 1-1 1-2V9a6 6 0 0 1 6-6M9 17v1a3 3 0 0 0 6 0v-1");
}

:global(.zq7hq1-vu) {
  stroke-opacity: 0.4;
  d: path("M15 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
