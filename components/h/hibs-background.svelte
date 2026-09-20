<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGO31zQeVP)" class="r4i437pya"/><path class="inra6pyue"/></g><defs><linearGradient id="SVGO31zQeVP" x1="11.714" x2="11.714" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="xyat4ib1w"/><stop offset="1" class="b5zrdhctb"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:hibs-background" {...props}></Icon>
<style>
:global(.b5zrdhctb) {
  stop-color: var(--svg-color--1a75bb, #1a75bb);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.inra6pyue) {
  fill: var(--svg-color--fff, #fff);
  d: path("M6 4a2 2 0 0 0-2 2v12a2 2 0 0 0 4 0V6a2 2 0 0 0-2-2m6 2.297a2 2 0 0 0-2 2.006v7.411a2 2 0 1 0 4 0V8.303a2 2 0 0 0-2-2.006m4 5.383c0-1.086.897-1.966 2-1.966s2 .88 2 1.966v6.354C20 19.12 19.103 20 18 20a1.98 1.98 0 0 1-2-1.966zM18 4a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.xyat4ib1w) {
  stop-color: var(--svg-color--25a9e0, #25a9e0);
}

</style>
