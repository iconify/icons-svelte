<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="djzh0xbac"/><path class="byyn3nb1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:chat-teardrop-text-duotone" {...props}></Icon>
<style>
:global(.byyn3nb1z) {
  d: path("M172 112a8 8 0 0 1-8 8H96a8 8 0 0 1 0-16h68a8 8 0 0 1 8 8m-8 24H96a8 8 0 0 0 0 16h68a8 8 0 0 0 0-16m68-12a100.11 100.11 0 0 1-100 100H48a16 16 0 0 1-16-16v-84a100 100 0 0 1 200 0m-16 0a84 84 0 0 0-168 0v84h84a84.09 84.09 0 0 0 84-84");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.djzh0xbac) {
  d: path("M224 124a92 92 0 0 1-92 92H48a8 8 0 0 1-8-8v-84a92 92 0 0 1 92-92a92 92 0 0 1 92 92");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
