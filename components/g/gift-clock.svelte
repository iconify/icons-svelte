<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="mbf6vr-el"/><path class="siq_r9b4a"/></g><circle class="bf9_qabtn"/><path class="f-l8bxkjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gift-clock" {...props}></Icon>
<style>
:global(.bf9_qabtn) {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
}

:global(.f-l8bxkjq) {
  d: path("M17.5 15.75v1.75l1.25 1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jf0axzbmx) {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

:global(.mbf6vr-el) {
  width: 17.5px;
  height: 4.25px;
  x: 3.25px;
  y: 7.25px;
  rx: 1.25px;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.siq_r9b4a) {
  d: path("M4.75 14h14.5v5.25a2 2 0 0 1-2 2H6.75a2 2 0 0 1-2-2ZM12 7.25v14m0-14H8.75a2 2 0 1 1 0-4c1.75 0 2.75 2 3.25 4m0 0h3.25a2 2 0 1 0 0-4c-1.75 0-2.75 2-3.25 4");
}

</style>
