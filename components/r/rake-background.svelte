<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="iidrg9b-u"/><path class="roo4_ibtz"/><path class="q656kf4fa"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:rake-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.iidrg9b-u) {
  fill: var(--svg-color--12cf9c, #12cf9c);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.q656kf4fa) {
  fill: var(--svg-color--67e0bf, #67e0bf);
  d: path("m10.2 4.2l2.05 7.3l7.38-1.905a8 8 0 0 0-.834-1.815L13.75 9.25l-1.365-5.24a8 8 0 0 0-2.185.195z");
}

:global(.roo4_ibtz) {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.07 5.03l2.43 9.72l9.5-2.78V12A8 8 0 1 1 8.07 5.03");
}

</style>
