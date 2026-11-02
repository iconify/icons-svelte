<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q7_w5f3zx"/><path class="d0983y84f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-tree-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.d0983y84f) {
  d: path("M20 5a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

:global(.q7_w5f3zx) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 11h3a1 1 0 0 1 0 2H5v1a3 3 0 0 0 3 3a1 1 0 0 1 0 2a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 14V6a1 1 0 0 1 2 0Z");
}

</style>
