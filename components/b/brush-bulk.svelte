<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yp1b9dl6h"/><path class="qefa9xb9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brush-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.qefa9xb9o) {
  d: path("M11 3v3a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m4 0v3a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0M6 9h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

:global(.yp1b9dl6h) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 15a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-1v4a3 3 0 1 1-6 0v-4Z");
}

</style>
