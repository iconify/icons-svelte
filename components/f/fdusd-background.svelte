<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bg6ngvbbo"/><path class="wpixbbb0p"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:fdusd-background" {...props}></Icon>
<style>
:global(.bg6ngvbbo) {
  fill: var(--svg-color--00e98d, #00e98d);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.wpixbbb0p) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.827 16.138h8.828V20H4.827zM19.173 4h-9.38v9.38h9.38v-3.31h-5.518V7.31h5.518z");
}

</style>
