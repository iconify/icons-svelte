<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uw5kuce7r"/><path class="qkig0y_8f"/><path class="sw6_egbdo"/><path class="fhbl5kbmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-horizontal-space-between-outline-regular" {...props}></Icon>
<style>
:global(.fhbl5kbmk) {
  d: path("M21 3v18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qkig0y_8f) {
  d: path("M6 7h4v10H6Z");
}

:global(.sw6_egbdo) {
  d: path("M14 7h4v10h-4Z");
}

:global(.uw5kuce7r) {
  d: path("M3 3v18");
}

</style>
