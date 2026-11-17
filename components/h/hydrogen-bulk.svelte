<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q393tzbsh"/><path class="knnhe3b7z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hydrogen-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.knnhe3b7z) {
  d: path("M14 4h-1v2a1 1 0 0 1-2 0V4h-1a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2m-4 9h4v-2a1 1 0 0 1 2 0v6a1 1 0 0 1-2 0v-2h-4v2a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Z");
}

:global(.q393tzbsh) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 13a8 8 0 0 1 16 0v6a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3Z");
}

</style>
