<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wei4hbwdb"/><path class="eh8x-4blr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-center-horizontal-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.eh8x-4blr) {
  d: path("M13 21a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Z");
}

:global(.wei4hbwdb) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 3h10a4 4 0 0 1 0 8H7a4 4 0 0 1 0-8m2 10h6a4 4 0 0 1 0 8H9a4 4 0 0 1 0-8");
}

</style>
