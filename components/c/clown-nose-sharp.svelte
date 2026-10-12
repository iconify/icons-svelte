<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dd5c3cpcd"/><circle class="hdr_b5byi"/><circle class="h79_orbgt"/><circle class="zs__krbjh"/><circle class="ff2w_2bef"/><circle class="wan3ixb9j"/><circle class="bkn29lj2b"/><circle class="adcsmfg4s"/><path class="hh5mhybyo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:clown-nose-sharp" {...props}></Icon>
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

:global(.hh5mhybyo) {
  d: path("M9 7.75V9m6-1.25V9m-5.25 7.25L12 17.375l2.25-1.125");
}

:global(.wan3ixb9j) {
  cx: 19.25px;
  cy: 15.75px;
  r: 1.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zs__krbjh) {
  cx: 19.25px;
  cy: 10.25px;
  r: 1.5px;
}

</style>
