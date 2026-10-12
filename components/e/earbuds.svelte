<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="deritttri"/><circle class="vxis36bae"/><path class="j_r6_1buk"/><path class="u3wlq3b1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:earbuds" {...props}></Icon>
<style>
:global(.deritttri) {
  cx: 7.25px;
  cy: 7.75px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j_r6_1buk) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 10.5v9.75m6-9.75v9.75");
}

:global(.u3wlq3b1j) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 7.25h.01m10.99 0h.01");
}

:global(.vxis36bae) {
  cx: 16.75px;
  cy: 7.75px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
