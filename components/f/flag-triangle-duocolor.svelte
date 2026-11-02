<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m1_xilbul"/><path class="sxjheol8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flag-triangle-duocolor" {...props}></Icon>
<style>
:global(.m1_xilbul) {
  stroke-opacity: 0.4;
  d: path("M6 15v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sxjheol8m) {
  d: path("M6 15V5c0-.919 1.081-1.46 2-1l8 4a1.118 1.118 0 0 1 0 2z");
}

</style>
