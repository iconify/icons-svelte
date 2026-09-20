<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h1lhfjjac"/><path clip-rule="evenodd" class="m5p6c8_ni"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:optopia-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.h1lhfjjac) {
  fill: var(--svg-color--ff1a2d, #ff1a2d);
  d: path("M24 0H0v24h24z");
}

:global(.m5p6c8_ni) {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M9.616 15.212a4 4 0 1 1 4.384.253v-.794l-3.584 2.11v1.736l-.8.8zm.8.64L14 13.743V9.808l-3.584 2.113zM20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
