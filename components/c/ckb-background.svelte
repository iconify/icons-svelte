<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="nss8x1mcs"/><path class="qiwomdbid"/><path class="lq85rkb9l"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:ckb-background" {...props}></Icon>
<style>
:global(.beaf9ac8r) {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lq85rkb9l) {
  fill: var(--svg-color--3cc68a, #3cc68a);
  d: path("M14.5 7.5v5.855l-8-8.25V13.5l3 3v-5.635l8 8.135v-8.5z");
}

:global(.nss8x1mcs) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 5v8.5h2.5V5zm13.5 5.5V19H20v-8.5zM12 5v5.81l2.5 2.575V7.5zm-2.5 5.72v5.78L12 19v-5.595z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.qiwomdbid) {
  fill: var(--svg-color--d8d8d8, #d8d8d8);
  d: path("M12 5h2.665L20 10.5h-2.5zm-8 8.5h2.5L12 19H9.335z");
}

</style>
