<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fr4ra8b7i"/><path class="te_1idb1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-candlestick-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fr4ra8b7i) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 6a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2ZM2 16a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Zm14 0a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Z");
}

:global(.te_1idb1x) {
  d: path("M11 5V3a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0M4 15v-3a1 1 0 0 1 2 0v3a1 1 0 0 1-2 0m7 0v-3a1 1 0 0 1 2 0v3a1 1 0 0 1-2 0m7 0v-3a1 1 0 0 1 2 0v3a1 1 0 0 1-2 0m0 6v-2a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0M4 20a1 1 0 0 1 2 0v1a1 1 0 0 1-2 0Z");
}

</style>
