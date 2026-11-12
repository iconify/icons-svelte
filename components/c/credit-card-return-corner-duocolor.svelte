<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vl-elwbyh"/><path class="kgw43-t1y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-return-corner-duocolor" {...props}></Icon>
<style>
:global(.kgw43-t1y) {
  d: path("M21 9V7a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h4M3 9h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vl-elwbyh) {
  stroke-opacity: 0.4;
  d: path("M21 13v2a2 2 0 0 1-2 2h-6m3-3l-3 3l3 3");
}

</style>
