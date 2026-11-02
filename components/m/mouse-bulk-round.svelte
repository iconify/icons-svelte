<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mzow7zb4w"/><path class="sbivg24wv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mouse-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.mzow7zb4w) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 9a7 7 0 1 1 14 0v6a7 7 0 1 1-14 0Z");
}

:global(.sbivg24wv) {
  d: path("M13 7v3a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0");
}

</style>
