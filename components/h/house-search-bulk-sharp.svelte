<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ai237mb3y"/><path class="acc1in20p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-search-bulk-sharp" {...props}></Icon>
<style>
:global(.acc1in20p) {
  d: path("m13.708 14.293l1.999 2a.999.999 0 1 1-1.414 1.414l-2-1.999a3 3 0 1 1 1.415-1.415m-3.415-.586a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

:global(.ai237mb3y) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.659 9.247c.217.19.341.465.341.753v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

</style>
