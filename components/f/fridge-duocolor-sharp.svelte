<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wui7iacqj"/><path class="ezi4ypbgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fridge-duocolor-sharp" {...props}></Icon>
<style>
:global(.ezi4ypbgy) {
  d: path("M5 3h14v18H5Zm0 7h14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wui7iacqj) {
  stroke-opacity: 0.4;
  d: path("M15 6v1m0 7v3");
}

</style>
