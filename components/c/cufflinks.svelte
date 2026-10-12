<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jc6oap-gd"/><circle class="dx6qgibjz"/><path class="rwplwb62a"/><rect class="ig_-qpv2p"/><rect class="i_rqi5bwp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cufflinks" {...props}></Icon>
<style>
:global(.dx6qgibjz) {
  cx: 17.5px;
  cy: 8.5px;
  r: 3.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_rqi5bwp) {
  width: 5.5px;
  height: 2.5px;
  x: 14.75px;
  y: 17.5px;
  rx: 1.25px;
}

:global(.ig_-qpv2p) {
  width: 5.5px;
  height: 2.5px;
  x: 3.75px;
  y: 17.5px;
  rx: 1.25px;
}

:global(.jc6oap-gd) {
  cx: 6.5px;
  cy: 8.5px;
  r: 3.75px;
}

:global(.rwplwb62a) {
  d: path("M6.5 12.25v5.25m11-5.25v5.25");
}

</style>
