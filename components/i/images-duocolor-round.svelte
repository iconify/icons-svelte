<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hovzczbga"/><path class="qyrppac0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:images-duocolor-round" {...props}></Icon>
<style>
:global(.hovzczbga) {
  stroke-opacity: 0.4;
  d: path("m3 17l3-3a2.83 2.83 0 0 1 4 0l1 1a1.414 1.414 0 0 0 2 0a1.414 1.414 0 0 1 2 0l2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qyrppac0c) {
  d: path("M7 3h10a4 4 0 0 1 4 4v10M3 11a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

</style>
