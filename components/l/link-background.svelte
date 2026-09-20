<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qlp3nfh9z"/><path class="hi5v994og"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:link-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.hi5v994og) {
  fill: var(--svg-color--fff, #fff);
  d: path("m12 4l6.43 3.851v7.794L11.082 20v-1.098l-5.496-3.285l-.016-7.72zm.008 13.316l4.585-2.715V8.894l-4.592-2.748L7.408 8.93v5.644z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.qlp3nfh9z) {
  fill: var(--svg-color--2e61de, #2e61de);
  d: path("M24 0H0v24h24z");
}

</style>
