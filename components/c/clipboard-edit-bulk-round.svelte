<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j90vb6xsh"/><path class="rbvdqr1un"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clipboard-edit-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.j90vb6xsh) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 9v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5");
}

:global(.rbvdqr1un) {
  d: path("M11 2h2a3 3 0 1 1 0 6h-2a3 3 0 1 1 0-6M8 16c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 11 19H9a1 1 0 0 1-1-1Z");
}

</style>
