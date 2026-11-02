<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a2tu2pn5x"/><path class="s4i9qqr5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-right-bulk-sharp" {...props}></Icon>
<style>
:global(.a2tu2pn5x) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3h12a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m4 10h8a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.s4i9qqr5y) {
  d: path("M21 3v18a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0");
}

</style>
