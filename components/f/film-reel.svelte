<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="icc1v1yqn"/><circle class="xttzr879b"/><circle class="fvsu8ubvu"/><circle class="p01uf6b6n"/><circle class="l6gcy4nyz"/><path class="ydc96fu9t"/><path class="e84hrrbda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:film-reel" {...props}></Icon>
<style>
:global(.e84hrrbda) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11 19.25l2.25 2h8");
}

:global(.fvsu8ubvu) {
  cx: 15.25px;
  cy: 11px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.icc1v1yqn) {
  cx: 11px;
  cy: 11px;
  r: 8.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l6gcy4nyz) {
  cx: 6.75px;
  cy: 11px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p01uf6b6n) {
  cx: 11px;
  cy: 15.25px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xttzr879b) {
  cx: 11px;
  cy: 6.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ydc96fu9t) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 11h.01");
}

</style>
