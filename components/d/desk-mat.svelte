<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q0_gb6qzx"/><path class="olsy2fksj"/><rect class="tkyx6ccqr"/><path class="z-kb47buq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:desk-mat" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.olsy2fksj) {
  d: path("M5.75 10.5h5m-5 3h5");
}

:global(.q0_gb6qzx) {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2px;
}

:global(.tkyx6ccqr) {
  width: 5px;
  height: 7px;
  x: 13.25px;
  y: 8.25px;
  rx: 2.5px;
}

:global(.z-kb47buq) {
  d: path("M15.75 8.25V11");
}

</style>
