<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fn6lefoka"/><path class="ghza94bcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-solar-panel-corner-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fn6lefoka) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.659 2.247l5.714 5A1.001 1.001 0 0 1 17.714 9H9v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0");
}

:global(.ghza94bcq) {
  d: path("M13 22a1 1 0 0 1-.992-1.124l1-8A1 1 0 0 1 14 12h6a1 1 0 0 1 .992.876l1 8A.997.997 0 0 1 21 22Zm3-8h-1.117l-.25 2H16Zm0 4h-1.617l-.25 2H16Zm2 2h1.867l-.25-2H18Zm1.367-4l-.25-2H18v2Z");
}

</style>
