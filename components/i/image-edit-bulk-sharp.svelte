<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="td1bzxb2d"/><path class="aapa57b3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:image-edit-bulk-sharp" {...props}></Icon>
<style>
:global(.aapa57b3y) {
  d: path("M10 10c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 14 14h-3a1 1 0 0 1-1-1Zm-5.707 4.293a1 1 0 0 1 1.414 0l6 6a.999.999 0 1 1-1.414 1.414L5 16.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.td1bzxb2d) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

</style>
