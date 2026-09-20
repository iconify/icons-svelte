<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGZIwx9zvt)" class="wtumn5b3p"/><defs><linearGradient id="SVGZIwx9zvt" x1="12.45" x2="9.75" y1="7.5" y2="15.6" gradientUnits="userSpaceOnUse"><stop class="qgzh5bb9g"/><stop offset=".12" class="rs-3iws3g"/><stop offset=".18" class="zjgk99b-g"/><stop offset=".24" class="ofl_-xb-p"/><stop offset=".3" class="qw_2y6x-p"/><stop offset=".37" class="wwasz5mot"/><stop offset=".45" class="om3e9bb_q"/><stop offset=".56" class="uwt5ebpbf"/><stop offset=".75" class="m-0ofacqa"/><stop offset=".91" class="u4xt3wbvr"/><stop offset="1" class="ji69y85_l"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:pop" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ji69y85_l) {
  stop-color: var(--svg-color--c379ad, #c379ad);
}

:global(.m-0ofacqa) {
  stop-color: var(--svg-color--7443b7, #7443b7);
}

:global(.ofl_-xb-p) {
  stop-color: var(--svg-color--cc83a1, #cc83a1);
}

:global(.om3e9bb_q) {
  stop-color: var(--svg-color--8851b7, #8851b7);
}

:global(.qgzh5bb9g) {
  stop-color: var(--svg-color--00bac9, #00bac9);
}

:global(.qw_2y6x-p) {
  stop-color: var(--svg-color--663fa9, #663fa9);
}

:global(.rs-3iws3g) {
  stop-color: var(--svg-color--2060b2, #2060b2);
}

:global(.u4xt3wbvr) {
  stop-color: var(--svg-color--8f48a9, #8f48a9);
}

:global(.uwt5ebpbf) {
  stop-color: var(--svg-color--e096ac, #e096ac);
}

:global(.wtumn5b3p) {
  d: path("M6.15 13.8h12.6V8.4H21v7.2H6.15zm-.9 1.8H3V8.4h14.85v1.8H5.25zm12.6-2.7v-1.8H6.15v1.8z");
}

:global(.wwasz5mot) {
  stop-color: var(--svg-color--3557b8, #3557b8);
}

:global(.zjgk99b-g) {
  stop-color: var(--svg-color--7046b2, #7046b2);
}

</style>
