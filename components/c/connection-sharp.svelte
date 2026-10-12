<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="wv5f_1brg"/><path class="r_2ezabni"/><circle class="nev2nabhe"/><path class="iqas_ll2b"/><circle class="f1cj5wo7i"/><path class="upylgbkbq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:connection-sharp" {...props}></Icon>
<style>
:global(.f1cj5wo7i) {
  cx: 19.25px;
  cy: 15.25px;
  r: 2px;
}

:global(.iqas_ll2b) {
  d: path("M2.75 21.25V19.5h4v1.75");
}

:global(.nev2nabhe) {
  cx: 4.75px;
  cy: 15.25px;
  r: 2px;
}

:global(.r_2ezabni) {
  d: path("M9 12.75c0-1 1.35-1.75 3-1.75s3 .75 3 1.75");
}

:global(.upylgbkbq) {
  d: path("M17.25 21.25V19.5h4v1.75");
}

:global(.wv5f_1brg) {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
