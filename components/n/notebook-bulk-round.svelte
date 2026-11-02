<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o3bby8bje"/><path class="ka7qkbcrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:notebook-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ka7qkbcrn) {
  d: path("M9 20a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0Zm3-13h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m0 4h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

:global(.o3bby8bje) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 21a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21Z");
}

</style>
