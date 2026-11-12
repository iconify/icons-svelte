<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m-ua3ebgj"/><path class="v-cy__q4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:image-warning-duocolor-sharp" {...props}></Icon>
<style>
:global(.m-ua3ebgj) {
  stroke-opacity: 0.4;
  d: path("M14 7v3m0 3h.01");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v-cy__q4i) {
  d: path("M3 3h18v18H3Zm0 14l4-4l8 8");
}

</style>
