<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="obago5bid"/><path class="l-cx87bba"/><path class="rl3f39odg"/><path class="x34_y0fwf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:help-point" {...props}></Icon>
<style>
:global(.l-cx87bba) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 7.25a2 2 0 1 1 2.9 1.8c-.55.3-.9.7-.9 1.3v.4");
}

:global(.obago5bid) {
  cx: 12px;
  cy: 8.75px;
  r: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rl3f39odg) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.6h.01");
}

:global(.x34_y0fwf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14.75v6.5m-3.5 0h7");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
