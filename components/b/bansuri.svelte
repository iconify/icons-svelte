<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="f6tap8avz"/><path class="jbnvukuau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bansuri" {...props}></Icon>
<style>
:global(.f6tap8avz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.84 20.34l13.5-13.5a2.25 2.25 0 0 0-3.18-3.18l-13.5 13.5a2.25 2.25 0 0 0 3.18 3.18");
}

:global(.jbnvukuau) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 15.5h.01m2.24-2.25h.01M13 11h.01m3.49-3.5h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
