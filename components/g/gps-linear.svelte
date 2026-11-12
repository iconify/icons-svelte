<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xtx0s6u8w"/><path class="jb8hy8b-t"/><path class="mhrx-fb4o"/><path class="hk3yrq41f"/><path class="cd5mfpgqy"/><path class="kk05o5b_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gps-linear" {...props}></Icon>
<style>
:global(.cd5mfpgqy) {
  d: path("M12 4V2");
}

:global(.hk3yrq41f) {
  d: path("M20 12L22 12");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jb8hy8b-t) {
  d: path("M15 12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12C9 10.3431 10.3431 9 12 9C13.6569 9 15 10.3431 15 12Z");
}

:global(.kk05o5b_l) {
  d: path("M12 22V20");
}

:global(.mhrx-fb4o) {
  d: path("M2 12L4 12");
}

:global(.xtx0s6u8w) {
  d: path("M20 12C20 16.4183 16.4183 20 12 20C7.58172 20 4 16.4183 4 12C4 7.58172 7.58172 4 12 4C16.4183 4 20 7.58172 20 12Z");
}

</style>
