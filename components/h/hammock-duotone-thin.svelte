<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="igf1wdb1b"/><path class="soc05fb5m"/><path class="episydb5i"/><path class="w77w8cbyi"/><path class="r3uz_wvor"/><path class="vvv_0v-7b"/><path class="auc4o2swl"/><path class="bu35rpbki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hammock-duotone-thin" {...props}></Icon>
<style>
:global(.auc4o2swl) {
  d: path("M4 8c0 8 16 8 16 0");
}

:global(.bu35rpbki) {
  d: path("M4 12c0 7 16 7 16 0");
}

:global(.episydb5i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8c0 8 16 8 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.igf1wdb1b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3uz_wvor) {
  d: path("M4 6v15");
}

:global(.soc05fb5m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 6v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vvv_0v-7b) {
  d: path("M20 6v15");
}

:global(.w77w8cbyi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12c0 7 16 7 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
