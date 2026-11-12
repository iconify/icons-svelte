<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="aope2d4kb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-pie-bulk" {...props}></Icon>
<style>
:global(.aope2d4kb) {
  d: path("M13 11h8a1 1 0 0 1 0 2h-6.586l4.293 4.293a.999.999 0 1 1-1.414 1.414l-6-6A1 1 0 0 1 11 12V3a1 1 0 0 1 2 0Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.riis51qtn) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
