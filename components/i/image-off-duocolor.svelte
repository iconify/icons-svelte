<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ge0pu2v_p"/><path class="j-lx_qqjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:image-off-duocolor" {...props}></Icon>
<style>
:global(.ge0pu2v_p) {
  stroke-opacity: 0.4;
  d: path("m3 17l7-7m5-2a1 1 0 1 0 2 0a1 1 0 0 0-2 0M2 2l20 20");
}

:global(.j-lx_qqjd) {
  d: path("M20 20c-.362.362-.448 1-1 1H5a2 2 0 0 1-2-2V5c0-.552.638-.638 1-1m5-1h10a2 2 0 0 1 2 2v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
