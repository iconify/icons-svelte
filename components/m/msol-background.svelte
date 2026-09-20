<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t4ghkxpoo"/><path clip-rule="evenodd" class="pa2ivlbwv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:msol-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.pa2ivlbwv) {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6.824 6.354H20l-3.294 2.823H4zm.001 8.47H19.53l-2.813 2.823H4zm9.881-4.235L4 10.59l2.825 2.821H19.53z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.t4ghkxpoo) {
  fill: var(--svg-color--308d8a, #308d8a);
  d: path("M24 0H0v24h24z");
}

</style>
