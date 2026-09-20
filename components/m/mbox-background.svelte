<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fik8txbgv"/><path class="y7n4qbcmm"/><path class="vp_ze_b4i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:mbox-background" {...props}></Icon>
<style>
:global(.fik8txbgv) {
  fill: var(--svg-color--b5c7ff, #b5c7ff);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.vp_ze_b4i) {
  fill: var(--svg-color--fff, #fff);
  d: path("m20 12.555l-4-2.333v3.888l4 2.333zm-8 0l-3.999-2.333v3.888l4 2.333z");
}

:global(.y7n4qbcmm) {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 11.112l-3.111-1.76l3.11-1.795l3.111 1.795zm-8 1.443l4-2.333v3.888l-4 2.333zm8 0l4-2.333v3.888l-4 2.333z");
}

</style>
