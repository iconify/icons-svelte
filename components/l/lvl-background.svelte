<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jfokftkbo"/><path class="ofgvlt13s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:lvl-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jfokftkbo) {
  fill: var(--svg-color--ffb313, #ffb313);
  d: path("M24 0H0v24h24z");
}

:global(.ofgvlt13s) {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.032 4h5.162v3.613H5.032zm0 6.194h8.774v3.612H5.032zm0 6.193h13.936V20H5.032z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
