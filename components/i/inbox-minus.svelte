<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="z3cxn1bbu"/><path class="vn1l890vq"/></g><path class="notrppkqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:inbox-minus" {...props}></Icon>
<style>
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

:global(.notrppkqh) {
  d: path("M14.75 17.5h5.5");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.vn1l890vq) {
  d: path("M2.75 13.25h4.4l1.1 2.2c.25.5.75.8 1.3.8h4.9c.55 0 1.05-.3 1.3-.8l1.1-2.2h4.4");
}

:global(.z3cxn1bbu) {
  d: path("m2.75 13.25l2.6-7.4a2.5 2.5 0 0 1 2.36-1.6h8.58a2.5 2.5 0 0 1 2.36 1.6l2.6 7.4v4.5a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5Z");
}

</style>
