<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="unapy8b0i"/><path clip-rule="evenodd" class="b6d7vy3_e"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:plume-background" {...props}></Icon>
<style>
:global(.b6d7vy3_e) {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4 4.001v6.36l2.254 2.274v-6.36l6.284.02l-2.253-2.274L4.001 4zM15.433 9.09v5.742l-2.255-2.273V6.815zm-6.286 6.34h5.693l-2.253-2.274H6.894zm9.49 2.606V12.32l-2.255-2.273v6.36l-6.284-.021l2.253 2.274l5.683.02l1.199 1.208L20 20l-.146-.737z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.unapy8b0i) {
  fill: var(--svg-color--ff3d00, #ff3d00);
  d: path("M24 0H0v24h24z");
}

</style>
