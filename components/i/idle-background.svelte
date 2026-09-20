<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="g2__8obzq"/><path class="jgjv8xbhj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:idle-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g2__8obzq) {
  fill: var(--svg-color--1b14dc, #1b14dc);
  d: path("M24 0H0v24h24z");
}

:global(.jgjv8xbhj) {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.556 17.333V4L6.222 7.156v10.177zm6.222-10.666h-5.334V20l5.334-3.155z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
