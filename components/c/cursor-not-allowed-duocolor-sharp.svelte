<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wfqzzweiu"/><path class="jdkg1gbhm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cursor-not-allowed-duocolor-sharp" {...props}></Icon>
<style>
:global(.jdkg1gbhm) {
  d: path("m3 3l12 4l-4 1l2 2l-3 3l-2-2l-1 4z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wfqzzweiu) {
  stroke-opacity: 0.4;
  d: path("M19 14a3.606 3.606 0 1 1-4 6a3.606 3.606 0 0 1 4-6m-4 6l4-6");
}

</style>
