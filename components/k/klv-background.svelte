<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="lb59vbcyz"/><path class="k7klzab2c"/><path class="sup7zacgw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:klv-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.k7klzab2c) {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 19.714H4V4.286z");
}

:global(.lb59vbcyz) {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 19.714h-7.703L20 12.285z");
}

:global(.mumfproca) {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.sup7zacgw) {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 19.714L16.148 16l.89-.857z");
  opacity: var(--svg-opacity--0-14, 0.14);
}

</style>
