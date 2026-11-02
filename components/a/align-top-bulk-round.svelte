<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cfll5pbhs"/><path class="n4vwsnj3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-top-bulk-round" {...props}></Icon>
<style>
:global(.cfll5pbhs) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 11v6a4 4 0 0 1-8 0v-6a4 4 0 0 1 8 0m10 0v2a4 4 0 0 1-8 0v-2a4 4 0 0 1 8 0");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.n4vwsnj3k) {
  d: path("M3 3h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
