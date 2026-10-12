<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="tbuwkfblz"/><path class="ekfvqi6-x"/></g><circle class="bf9_qabtn"/><path class="f-l8bxkjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:notebook-clock" {...props}></Icon>
<style>
:global(.bf9_qabtn) {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
}

:global(.ekfvqi6-x) {
  d: path("M3.75 7.25h3.5M3.75 12h3.5m-3.5 4.75h3.5m3.75-9h4.5");
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

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.tbuwkfblz) {
  width: 13.5px;
  height: 18.5px;
  x: 5.75px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
