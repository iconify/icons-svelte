<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="if3xfnbtz"/><path class="np6vonbsu"/><path class="q_nfnc6mi"/><path class="ekpyzob7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:alert-banner" {...props}></Icon>
<style>
:global(.ekpyzob7n) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 12h7.25");
}

:global(.if3xfnbtz) {
  width: 18.5px;
  height: 11px;
  x: 2.75px;
  y: 6.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.np6vonbsu) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 9.5v3");
}

:global(.q_nfnc6mi) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
