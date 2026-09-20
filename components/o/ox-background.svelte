<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wauyqzb0i"/><path class="dwu4sjnrr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:ox-background" {...props}></Icon>
<style>
:global(.dwu4sjnrr) {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.506 12.005a5.5 5.5 0 0 1-7.775 5.01a1 1 0 0 0-.47-.1c-1.135.075-2.15.54-2.745.91a8 8 0 1 0-.5-.515a3.05 3.05 0 0 0 1.075-2.69a1 1 0 0 0-.09-.33a5.5 5.5 0 1 1 10.505-2.285");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.wauyqzb0i) {
  fill: var(--svg-color--0057ff, #0057ff);
  d: path("M24 0H0v24h24z");
}

</style>
