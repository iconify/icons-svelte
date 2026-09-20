<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="be_841b2w"/><path class="gmbgh4b_f"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:cmdx-background" {...props}></Icon>
<style>
:global(.be_841b2w) {
  fill: var(--svg-color--ff424e, #ff424e);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gmbgh4b_f) {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.733 5.03v1.903h1.595V5.867h7.83l-1.723 1.6H4.757c-.426 0-.757.25-.757.672v10.827c0 .426.33.767.757.767H15.92l3.862-3.557c.453-.416.154-1.243-.47-1.243H9.328V9.6h-1.6v6.176c0 .427.181.757.608.757h8.89l-1.807 1.6H5.6V9.067h10.32l3.862-3.627c.453-.416.154-1.173-.47-1.173H8.336c-.427 0-.608.34-.608.762z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
