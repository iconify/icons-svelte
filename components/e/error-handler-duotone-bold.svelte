<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nur-ljbdo"/><path class="qrltb1_5z"/><path class="b0oa_xphd"/><path class="u33kgqbtd"/><path class="cmz4hzb5r"/><path class="r-k_ekbaq"/><path class="f9t4wkbqv"/><path class="ugh4qacil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:error-handler-duotone-bold" {...props}></Icon>
<style>
:global(.b0oa_xphd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 14 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cmz4hzb5r) {
  d: path("M2 12h6l4 -4h5");
}

:global(.f9t4wkbqv) {
  d: path("m19 14 3 3");
}

:global(.nur-ljbdo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h6l4 -4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qrltb1_5z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 12 4 4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r-k_ekbaq) {
  d: path("m8 12 4 4h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u33kgqbtd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m22 14 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ugh4qacil) {
  d: path("m22 14 -3 3");
}

</style>
