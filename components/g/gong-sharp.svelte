<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uma8ent2e"/><circle class="ms6me1bpn"/><circle class="yjztigbem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gong-sharp" {...props}></Icon>
<style>
:global(.ms6me1bpn) {
  cx: 12px;
  cy: 12.5px;
  r: 5.5px;
}

:global(.uma8ent2e) {
  d: path("M3.25 21.25V2.75h17.5v18.5M8.5 2.75l1.25 4.73m5.75-4.73l-1.25 4.73");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yjztigbem) {
  cx: 12px;
  cy: 12.5px;
  r: 2px;
}

</style>
