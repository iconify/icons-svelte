<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dhpxnuokf"/><path class="wdi_wfbtz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-gantt-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.dhpxnuokf) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 19h17a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0Z");
}

:global(.wdi_wfbtz) {
  d: path("M13 7a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm4 4a1 1 0 0 1 0 2h-7a1 1 0 0 1 0-2Zm3 6h-6a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2");
}

</style>
