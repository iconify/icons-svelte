<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jhy0_rbnw"/><path class="e8qphwbni"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:floor-background" {...props}></Icon>
<style>
:global(.e8qphwbni) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 11.059h16v1.882H4z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jhy0_rbnw) {
  fill: var(--svg-color--00f3d5, #00f3d5);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
