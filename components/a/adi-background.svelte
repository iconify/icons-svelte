<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGjiMxJewc)" class="r4i437pya"/><path class="crtmfrbud"/></g><defs><linearGradient id="SVGjiMxJewc" x1="12" x2="12" y1="0" y2="24" gradientUnits="userSpaceOnUse"><stop class="jpp7j9b0m"/><stop offset="1" class="uoxpj2blc"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:adi-background" {...props}></Icon>
<style>
:global(.crtmfrbud) {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.932 11.841c.06.098.06.22 0 .317l-4.67 7.694a.308.308 0 0 1-.525 0l-4.67-7.693a.31.31 0 0 1 0-.317l4.67-7.694a.308.308 0 0 1 .526 0zm-7.669-.307a.306.306 0 0 0 .263.464h4.948c.24 0 .387-.26.263-.464l-2.474-4.076a.308.308 0 0 0-.526 0zM12 9.376a.87.87 0 1 1 .001 1.742A.87.87 0 0 1 12 9.376");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jpp7j9b0m) {
  stop-color: var(--svg-color--fe7109, #fe7109);
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.uoxpj2blc) {
  stop-color: var(--svg-color--003bff, #003bff);
}

</style>
