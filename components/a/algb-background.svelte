<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y59sxsm9r"/><path class="kq36gib9x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:algb-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.kq36gib9x) {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.765 4.47v10.118L4 19.058zm.47 0v10.118L20 19.058zM12 15.06l-7.765 4.47h15.53z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.y59sxsm9r) {
  fill: var(--svg-color--b41870, #b41870);
  d: path("M24 0H0v24h24z");
}

</style>
