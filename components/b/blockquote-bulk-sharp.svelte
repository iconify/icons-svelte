<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x71w8dboq"/><path class="q52ufyo2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:blockquote-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.q52ufyo2q) {
  d: path("M20 5a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm-4 4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Z");
}

:global(.x71w8dboq) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0");
}

</style>
