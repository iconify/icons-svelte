<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i2jncywhw"/><path class="d5b4fcc2f"/><path class="aqx3gwb_o"/><path class="jtcv4c9tp"/><path class="kc767bc_i"/><path class="o2k1qictf"/><path class="grgwcd1mp"/><path class="z9ittvbis"/><path class="h4br4z40f"/><path class="e0fatccfd"/><path class="sdu5ckfnu"/><path class="sxnekjbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:golden-hour-duotone-bold" {...props}></Icon>
<style>
:global(.aqx3gwb_o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d5b4fcc2f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e0fatccfd) {
  d: path("M18 12h4");
}

:global(.grgwcd1mp) {
  d: path("M7.5 17a4.5 4.5 0 0 1 9 0");
}

:global(.h4br4z40f) {
  d: path("M2 12h4");
}

:global(.i2jncywhw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.5 17a4.5 4.5 0 0 1 9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jtcv4c9tp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kc767bc_i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 6 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o2k1qictf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 6 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sdu5ckfnu) {
  d: path("m5 6 3 3");
}

:global(.sxnekjbzh) {
  d: path("m19 6 -3 3");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
