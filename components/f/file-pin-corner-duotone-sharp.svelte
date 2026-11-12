<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vge47hz4y"/><path class="fmvoncb9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-pin-corner-duotone-sharp" {...props}></Icon>
<style>
:global(.fmvoncb9s) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H5v18h4m4-18l6 6m-6-6v6h6m-4 4h4v3l2 2h-8l2-2zm-1 0h6m-3 5v3");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.vge47hz4y) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 2h8c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-9v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1m8 2v4h4Zm6 9v3l2 2h-8l2-2v-3Z");
}

</style>
