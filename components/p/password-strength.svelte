<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="llx3q4izi"/><path class="k5srfkbfj"/><path class="ra_g3klqd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:password-strength" {...props}></Icon>
<style>
:global(.k5srfkbfj) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 9.25h.01m4.49 0h.01m4.49 0h.01");
}

:global(.llx3q4izi) {
  width: 18.5px;
  height: 7.5px;
  x: 2.75px;
  y: 5.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.ra_g3klqd) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 18.5H5m3 0h3.5m3 0h6");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
