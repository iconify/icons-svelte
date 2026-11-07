<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="afqo38bdn"/><path class="a603h4tgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-notes-double-duotone-sharp" {...props}></Icon>
<style>
:global(.a603h4tgb) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18a3 3 0 1 0 6 0a3 3 0 0 0-6 0m12-2a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6 2V7l12-4v13M9 12l12-4");
}

:global(.afqo38bdn) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 19a3 3 0 1 1 0-6a3 3 0 0 1 0 6M6 21a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

:global(.ft5dv1b6b) {
  fill: none;
}

</style>
