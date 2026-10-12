<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="op5c37b6j"/><path class="t2canbbyo"/><circle class="zhvhhokwo"/><path class="qnd9t7bws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cochlear-implant" {...props}></Icon>
<style>
:global(.op5c37b6j) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 20.25c3 0 4-2 4.5-4.5s3.5-3.5 3.5-7a6 6 0 0 0-12 0");
}

:global(.qnd9t7bws) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 15.5h.01");
}

:global(.t2canbbyo) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9a2.5 2.5 0 0 1 5 0c0 1.5-1.5 2-1.5 3.5m4.75-3.75c1.75.75 2.75 2.25 2.75 4");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zhvhhokwo) {
  cx: 18.5px;
  cy: 15.5px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
