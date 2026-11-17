<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p0g9bbcsi"/><path class="ea3r3s0yr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ceiling-light-duocolor-sharp" {...props}></Icon>
<style>
:global(.ea3r3s0yr) {
  d: path("M3 16a9 9 0 0 1 18 0Zm9-13v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p0g9bbcsi) {
  stroke-opacity: 0.4;
  d: path("M16 16a4 4 0 1 1-8 0");
}

</style>
