<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pkcxx5m2i"/><path class="td9ir9nnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:option-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.pkcxx5m2i) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 6h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

:global(.td9ir9nnc) {
  d: path("M9 6c.351 0 .677.184.857.486L15.566 16H21a1 1 0 0 1 0 2h-6a1 1 0 0 1-.857-.486L8.434 8H3a1 1 0 0 1 0-2Z");
}

</style>
