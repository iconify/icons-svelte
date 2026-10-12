<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)"><path class="mbf2pm3_i"/><path class="zbm7pqbjy"/></g><path class="uzvaxo9-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:car-edit" {...props}></Icon>
<style>
:global(.jf0axzbmx) {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

:global(.mbf2pm3_i) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.5L5.6 7.1a2 2 0 0 1 1.9-1.35h9a2 2 0 0 1 1.9 1.35l1.85 5.4v4.75a1 1 0 0 1-1 1H4.75a1 1 0 0 1-1-1Zm2.75 5.75v2.5m11-2.5v2.5m-13.25-9.5h15.5");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.uzvaxo9-g) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.25 19.75l.5-2.25l2.5-2.5A1.24 1.24 0 0 1 20 16.75l-2.5 2.5Zm1-2.75L18 18.75");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zbm7pqbjy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 14.75h.01");
}

</style>
