<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="fi0i07b4o"/><path class="h1wnxrb-e"/><path class="y-r00cryc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:channel-guide" {...props}></Icon>
<style>
:global(.fi0i07b4o) {
  width: 18.5px;
  height: 15.5px;
  x: 2.75px;
  y: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.h1wnxrb-e) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 8.25h.01M6 12h.01M6 15.75h.01");
}

:global(.y-r00cryc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 8.25h8m-8 7.5h6M9.5 12h8");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
