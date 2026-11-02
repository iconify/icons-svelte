<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q6g0-bbmu"/><path class="g05e12-_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-dot-duocolor-sharp" {...props}></Icon>
<style>
:global(.g05e12-_z) {
  d: path("M21 13v6H3V5h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q6g0-bbmu) {
  stroke-opacity: 0.4;
  d: path("m3 5l6 6h4m2-5a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
