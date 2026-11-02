<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cr4z7vbxc"/><path class="g-oss6b3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:frame-bulk" {...props}></Icon>
<style>
:global(.cr4z7vbxc) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 7a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.g-oss6b3q) {
  d: path("M8 7a1 1 0 0 1-1 1H3a1 1 0 0 1 0-2h3V3a1 1 0 0 1 2 0Zm10-4v3h3a1 1 0 0 1 0 2h-4a1 1 0 0 1-1-1V3a1 1 0 0 1 2 0M7 16a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0v-3H3a1 1 0 0 1 0-2Zm10 0h4a1 1 0 0 1 0 2h-3v3a1 1 0 0 1-2 0v-4a1 1 0 0 1 1-1");
}

</style>
