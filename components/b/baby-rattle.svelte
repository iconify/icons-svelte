<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="kny-18b_w"/><path class="ws9qpcbzb"/><path class="tdhqeuq6x"/><circle class="dd59-ably"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:baby-rattle" {...props}></Icon>
<style>
:global(.dd59-ably) {
  cx: 5.25px;
  cy: 18.75px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kny-18b_w) {
  cx: 14.75px;
  cy: 9.25px;
  r: 6.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tdhqeuq6x) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.15 13.85l-3.4 3.4");
}

:global(.ws9qpcbzb) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.5 8h.01m4.24 2.5h.01m-2.26 2h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
