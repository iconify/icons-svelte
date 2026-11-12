<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ctd-kcczy"/><path class="u058ycbqw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:earbuds-duocolor-sharp" {...props}></Icon>
<style>
:global(.ctd-kcczy) {
  stroke-opacity: 0.4;
  d: path("M6 7h.01M18 7h.01");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u058ycbqw) {
  d: path("M6 4c2 0 4 1 4 3v13c0 1-2 1-2 0V10H6q-3 0-3-3t3-3m12 0c-2 0-4 1-4 3v13c0 1 2 1 2 0V10h2q3 0 3-3t-3-3");
}

</style>
