<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="i1_1w_w8m"/><path class="p3m05pbms"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:quidd-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.i1_1w_w8m) {
  fill: var(--svg-color--6b10d7, #6b10d7);
  d: path("M24 0H0v24h24z");
}

:global(.p3m05pbms) {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.706 18.47a8 8 0 1 0-2.353 1.176v-3.572A4.706 4.706 0 1 1 16.706 12zM12 14.352a2.353 2.353 0 1 0 0-4.706a2.353 2.353 0 0 0 0 4.706");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
