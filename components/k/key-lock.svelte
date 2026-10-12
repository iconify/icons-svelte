<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)"><circle class="e9pwlacgz"/><path class="gi6lp8bso"/><path class="ssv44kbxz"/></g><rect class="rol6ayb1l"/><path class="gdbqatcys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:key-lock" {...props}></Icon>
<style>
:global(.e9pwlacgz) {
  cx: 8px;
  cy: 16px;
  r: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.gdbqatcys) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 17v-1a1.5 1.5 0 0 1 3 0v1");
}

:global(.gi6lp8bso) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 16h.01");
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

:global(.rol6ayb1l) {
  width: 5.5px;
  height: 4px;
  x: 14.75px;
  y: 17px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.ssv44kbxz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.75 12.25l8.5-8.5m-3 3L19.5 9m-4.75.25L16.5 11");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
