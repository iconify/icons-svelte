<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="xqkiicbwe"/><path class="msb4-ibai"/></g><circle class="bf9_qabtn"/><path class="f-l8bxkjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:headphones-clock" {...props}></Icon>
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

:global(.msb4-ibai) {
  d: path("M3.75 14.25V12a8.25 8.25 0 0 1 16.5 0v2.25");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.xqkiicbwe) {
  width: 4.5px;
  height: 7px;
  x: 3.75px;
  y: 13.25px;
  rx: 2px;
}

</style>
