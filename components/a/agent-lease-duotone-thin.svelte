<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rcsz11k7v"/><path class="vdkmp2b9k"/><path class="u5q3xebkh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-lease-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rcsz11k7v) {
  fill: currentColor;
  d: path("M9 14h6l-6 6h6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u5q3xebkh) {
  d: path("M9 14h6l-6 6h6Z");
}

:global(.vdkmp2b9k) {
  d: path("M13.9 2.42a4.5 4.5 0 1 1 -3.8 0");
}

</style>
