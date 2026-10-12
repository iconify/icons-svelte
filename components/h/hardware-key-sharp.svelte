<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="w6bc2rqej"/><path class="ed-xnxz9s"/><circle class="ctk1fcczq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hardware-key-sharp" {...props}></Icon>
<style>
:global(.ctk1fcczq) {
  cx: 12px;
  cy: 12px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ed-xnxz9s) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 12h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.w6bc2rqej) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5H17.5v9H2.75zm14.75 2h3.75v5H17.5z");
}

</style>
