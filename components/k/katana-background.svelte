<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGWu80AbzZ)" class="t_ev7s-sv"/><path class="odyylhbnv"/></g><defs><linearGradient id="SVGWu80AbzZ" x1="12" x2="12" y1="0" y2="24" gradientUnits="userSpaceOnUse"><stop offset=".09" class="vy0k_7b8y"/><stop offset=".558" class="sbqdwex4c"/><stop offset=".814" class="u65a-1bxo"/><stop offset="1" class="asyfvob6k"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:katana-background" {...props}></Icon>
<style>
:global(.asyfvob6k) {
  stop-color: var(--svg-color--c5eafc, #c5eafc);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.odyylhbnv) {
  fill: var(--svg-color--f6ff0d, #f6ff0d);
  d: path("M10.792 9.575L13.986 4h3.196l-2.397 7.98H12.41l6.39 3.192L15.584 20l-4.792-5.612v3.976H5.2l1.917-6.384H5.2L7.596 4h3.196z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.sbqdwex4c) {
  stop-color: var(--svg-color--0441b2, #0441b2);
}

:global(.t_ev7s-sv) {
  d: path("M0 0h24v24H0z");
}

:global(.u65a-1bxo) {
  stop-color: var(--svg-color--019eed, #019eed);
}

:global(.vy0k_7b8y) {
  stop-color: var(--svg-color--101631, #101631);
}

</style>
