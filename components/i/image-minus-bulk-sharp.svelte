<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="td1bzxb2d"/><path class="zn9zbdcph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:image-minus-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.td1bzxb2d) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

:global(.zn9zbdcph) {
  d: path("M12 8h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2m-9.707 8.293l4-4a1 1 0 0 1 1.414 0l8 8a.999.999 0 1 1-1.414 1.414L7 14.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414");
}

</style>
