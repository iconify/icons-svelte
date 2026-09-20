<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="eucedkani"/><path class="ylvu--yfl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:flare-background" {...props}></Icon>
<style>
:global(.eucedkani) {
  fill: var(--svg-color--e62058, #e62058);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.ylvu--yfl) {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.892 10.01H7.999A3.99 3.99 0 0 0 4 13.903c0 .057.044.105.105.105h7.893a3.99 3.99 0 0 0 3.999-3.897a.106.106 0 0 0-.105-.105zM19.891 4H8a3.986 3.986 0 0 0-3.995 3.897c0 .057.044.105.1.105h11.897a3.99 3.99 0 0 0 4-3.897a.106.106 0 0 0-.106-.105zM6.002 20a2.005 2.005 0 0 0 2.001-2.008a2.005 2.005 0 0 0-2.001-2.007A2.005 2.005 0 0 0 4 17.992C4 19.102 4.896 20 6.002 20");
}

</style>
