<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a6mxqbbot"/><path class="kzb8stbhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rewind-duotone-sharp" {...props}></Icon>
<style>
:global(.a6mxqbbot) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m3 12l9-5v10Zm9 0l9-5v10Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.kzb8stbhk) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m21 7l-9 5l9 5Zm-9 0l-9 5l9 5Z");
}

</style>
