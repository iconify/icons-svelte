<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="nvq1h_b2w"/><path class="lnlqdnb3m"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:gmpd-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lnlqdnb3m) {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 8.103H7.86L4 9.333h5.916l-2.749 6.564h9.846l1.887-4.513h-5.694l-.517 1.231h4.296l-.862 2.052H9.087l2.232-5.334h8.164z");
}

:global(.nvq1h_b2w) {
  fill: var(--svg-color--ffb800, #ffb800);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
