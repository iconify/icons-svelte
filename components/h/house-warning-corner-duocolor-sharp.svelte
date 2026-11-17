<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e906b4bdd"/><path class="g5s6ahb7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-warning-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.e906b4bdd) {
  stroke-opacity: 0.4;
  d: path("M17 14v4m0 3h.01");
}

:global(.g5s6ahb7t) {
  d: path("M8 21H4V10l8-7l5.714 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
