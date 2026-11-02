<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a57wzobvd"/><path class="qhevnvmwo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:parasol-duocolor" {...props}></Icon>
<style>
:global(.a57wzobvd) {
  stroke-opacity: 0.4;
  d: path("m12 13l4 8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qhevnvmwo) {
  d: path("M4 17a8.944 8.944 0 1 1 16-8Zm-1 4h18");
}

</style>
