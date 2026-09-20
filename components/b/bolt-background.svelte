<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="nco2l07ug"/><path class="kqqm5xojg"/><path class="jn-bikb1w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:bolt-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jn-bikb1w) {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 4L7.733 8.615l5.19 4.308L4 20l12-4.616l-1.23-7.077z");
}

:global(.kqqm5xojg) {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.733 16.618V9.01l4.694 3.915z");
}

:global(.nco2l07ug) {
  fill: var(--svg-color--280c9c, #280c9c);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
