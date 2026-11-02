<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wnpw2mb8u"/><path class="v1mmytbcw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paint-roller-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.v1mmytbcw) {
  d: path("M17 5h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-8v1h1a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h1v-2a1 1 0 0 1 1-1h8V7h-3a1 1 0 0 1 0-2m-6 15h2v-4h-2Z");
}

:global(.wnpw2mb8u) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 2a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm-7 12h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1");
}

</style>
