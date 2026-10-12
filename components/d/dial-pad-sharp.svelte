<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="z8zuirbke"/><circle class="lyxk1-6fp"/><circle class="g7l21hbkz"/><circle class="eyov16lqc"/><circle class="mp3z433gx"/><circle class="d_t4aybrb"/><circle class="rhon0acgv"/><circle class="jep-trbsd"/><circle class="tz_u_rbas"/><circle class="eycbyybhn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dial-pad-sharp" {...props}></Icon>
<style>
:global(.d_t4aybrb) {
  cx: 18.5px;
  cy: 9.25px;
  r: 1.4px;
}

:global(.eycbyybhn) {
  cx: 12px;
  cy: 19.25px;
  r: 1.4px;
}

:global(.eyov16lqc) {
  cx: 5.5px;
  cy: 9.25px;
  r: 1.4px;
}

:global(.g7l21hbkz) {
  cx: 18.5px;
  cy: 4.25px;
  r: 1.4px;
}

:global(.jep-trbsd) {
  cx: 12px;
  cy: 14.25px;
  r: 1.4px;
}

:global(.lyxk1-6fp) {
  cx: 12px;
  cy: 4.25px;
  r: 1.4px;
}

:global(.mp3z433gx) {
  cx: 12px;
  cy: 9.25px;
  r: 1.4px;
}

:global(.rhon0acgv) {
  cx: 5.5px;
  cy: 14.25px;
  r: 1.4px;
}

:global(.tz_u_rbas) {
  cx: 18.5px;
  cy: 14.25px;
  r: 1.4px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z8zuirbke) {
  cx: 5.5px;
  cy: 4.25px;
  r: 1.4px;
}

</style>
