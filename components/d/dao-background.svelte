<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGSPgvPelS)" class="r4i437pya"/><path class="eh-bvq-ud"/></g><defs><linearGradient id="SVGSPgvPelS" x1="4" x2="20" y1="11.998" y2="11.998" gradientUnits="userSpaceOnUse"><stop class="j0mjvbbqj"/><stop offset="1" class="adh00bbpd"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:dao-background" {...props}></Icon>
<style>
:global(.adh00bbpd) {
  stop-color: var(--svg-color--48d4ff, #48d4ff);
}

:global(.eh-bvq-ud) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 18.249L9.643 7.892l4.982-2.163l-5.652 10.349zm5.626-2.361l4.282-7.866l2.452 2.37l-4.238 7.878zm7.204-5.268L20 11.766l-1.587 2.867l-3.845.13z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.j0mjvbbqj) {
  stop-color: var(--svg-color--4086ff, #4086ff);
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

</style>
