<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lv6gjzbhq"/><circle class="gkmarkbih"/><circle class="ivnrysbyn"/><path class="mccm49fzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blush-compact" {...props}></Icon>
<style>
:global(.gkmarkbih) {
  cx: 12px;
  cy: 15.25px;
  r: 6px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ivnrysbyn) {
  cx: 12px;
  cy: 15.25px;
  r: 3.5px;
}

:global(.lv6gjzbhq) {
  d: path("M12 2.75a6 2 0 1 1 0 4a6 2 0 1 1 0-4m-2 4v2.5m4-2.5v2.5");
}

:global(.mccm49fzr) {
  d: path("M10.25 15.5c.9-1.25 2.6-1.25 3.5 0");
}

</style>
