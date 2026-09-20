<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vdkmp2b9k"/><path class="u5q3xebkh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-lease-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u5q3xebkh) {
  d: path("M9 14h6l-6 6h6Z");
}

:global(.vdkmp2b9k) {
  d: path("M13.9 2.42a4.5 4.5 0 1 1 -3.8 0");
}

</style>
