<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vmfev6bhz"/><path class="anav68jbm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:lrc-background" {...props}></Icon>
<style>
:global(.anav68jbm) {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.326 5.882v12.237L4 13.773zm.001 12.236l5.026-4.345l-1.462-2.296H20z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.vmfev6bhz) {
  fill: var(--svg-color--1f63ff, #1f63ff);
  d: path("M24 0H0v24h24z");
}

</style>
