<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dd5c3cpcd"/><circle class="hdr_b5byi"/><circle class="h79_orbgt"/><circle class="zs__krbjh"/><circle class="ff2w_2bef"/><circle class="wan3ixb9j"/><circle class="bkn29lj2b"/><circle class="adcsmfg4s"/><path class="tjcc2qbzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:clown-nose" {...props}></Icon>
<style>
:global(.adcsmfg4s) {
  cx: 12px;
  cy: 11.75px;
  r: 2px;
}

:global(.bkn29lj2b) {
  cx: 12px;
  cy: 12.5px;
  r: 6.75px;
}

:global(.dd5c3cpcd) {
  cx: 4.75px;
  cy: 10.25px;
  r: 1.5px;
}

:global(.ff2w_2bef) {
  cx: 19.75px;
  cy: 13px;
  r: 1.5px;
}

:global(.h79_orbgt) {
  cx: 4.75px;
  cy: 15.75px;
  r: 1.5px;
}

:global(.hdr_b5byi) {
  cx: 4.25px;
  cy: 13px;
  r: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tjcc2qbzo) {
  d: path("M9 7.75V9m6-1.25V9m-5.25 7.25q2.25 1.125 4.5 0");
}

:global(.wan3ixb9j) {
  cx: 19.25px;
  cy: 15.75px;
  r: 1.5px;
}

:global(.zs__krbjh) {
  cx: 19.25px;
  cy: 10.25px;
  r: 1.5px;
}

</style>
