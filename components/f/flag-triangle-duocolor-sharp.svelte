<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m1_xilbul"/><path class="s5c46mbxl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flag-triangle-duocolor-sharp" {...props}></Icon>
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

:global(.s5c46mbxl) {
  d: path("M6 15V3l12 6z");
}

</style>
