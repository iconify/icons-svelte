<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGUGrAUd9F)" class="r4i437pya"/><path class="schlavb2h"/></g><defs><linearGradient id="SVGUGrAUd9F" x1="-.034" x2="24.282" y1=".204" y2="24.681" gradientUnits="userSpaceOnUse"><stop class="wwpx0ybmw"/><stop offset="1" class="toq8x0ble"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:exodus-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.schlavb2h) {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 8.467L13.062 4v2.498l4.45 2.84l-.523 1.627h-3.927v2.07h3.927l.524 1.627l-4.451 2.84V20L20 15.547l-1.135-3.54zM7.025 13.035h3.913v-2.07H7.011L6.5 9.338l4.437-2.84V4L4 8.467l1.135 3.54L4 15.547L10.953 20v-2.498l-4.451-2.84z");
}

:global(.toq8x0ble) {
  stop-color: var(--svg-color--2e6af3, #2e6af3);
}

:global(.wwpx0ybmw) {
  stop-color: var(--svg-color--8c64fb, #8c64fb);
}

</style>
