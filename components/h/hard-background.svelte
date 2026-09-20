<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tf6xern2l"/><path class="p18bn_73d"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:hard-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.p18bn_73d) {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.231 4h3.077v6.154h7.385V4h3.076v16h-3.076v-6.77H8.308V20H5.23z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.tf6xern2l) {
  fill: var(--svg-color--441f67, #441f67);
  d: path("M24 0H0v24h24z");
}

</style>
