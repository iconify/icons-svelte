<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="awqg98bar"/><path class="mqh2f6n-y"/><path class="om2raabrv"/><path class="kjj2pe0fr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:battery-charging-duotone-bold" {...props}></Icon>
<style>
:global(.awqg98bar) {
  fill: currentColor;
  d: path("M2 9a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kjj2pe0fr) {
  d: path("m11 9 -3 3h3l-3 3");
}

:global(.mqh2f6n-y) {
  d: path("M2 9a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.om2raabrv) {
  d: path("M20 10v4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
