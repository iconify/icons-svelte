<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gslogdcho"/><path clip-rule="evenodd" class="j15sj5-oj"/><path class="it_y3kiee"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:dola-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gslogdcho) {
  fill: var(--svg-color--ffbb51, #ffbb51);
  d: path("M24 0H0v24h24z");
}

:global(.it_y3kiee) {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.25 4h2.055l-5.75 16H7.5zm3 0h2.055l-5.75 16H10.5z");
}

:global(.j15sj5-oj) {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.5 5H9.79L5 18h7.5a6.5 6.5 0 0 0 0-13m0 1.5H11l-3.75 10h5.25a5 5 0 1 0 0-10");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
