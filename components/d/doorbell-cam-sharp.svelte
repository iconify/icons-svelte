<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vf785v0lm"/><circle class="t66mq7qpn"/><path class="nntrnih8q"/><path class="fuldhtbew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:doorbell-cam-sharp" {...props}></Icon>
<style>
:global(.fuldhtbew) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 16a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 1 1 3.5 0");
}

:global(.nntrnih8q) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8.5h.01");
}

:global(.t66mq7qpn) {
  cx: 12px;
  cy: 8.5px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vf785v0lm) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.75h11.5v18.5H6.25z");
}

</style>
