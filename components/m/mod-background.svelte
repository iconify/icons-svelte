<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xzsyrjbmk"/><path class="xm70evkqw"/><path class="nrpop674w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:mod-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.nrpop674w) {
  fill: var(--svg-color--fff, #fff);
  d: path("m6 20l7.826-7.961l-7.554-7.675L6 4.09z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.xm70evkqw) {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.913 10.165L18 16.355V4z");
}

:global(.xzsyrjbmk) {
  fill: var(--svg-color--253750, #253750);
  d: path("M24 0H0v24h24z");
}

</style>
