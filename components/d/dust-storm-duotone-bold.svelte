<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plajqrbag"/><path class="otysgl0gj"/><path class="aszcawbfm"/><path class="u-xjqw_1i"/><path class="jlsz29kli"/><path class="ebnbsgm1q"/><path class="timme522h"/><path class="idl7fxbhb"/><path class="vzfmp7bra"/><path class="ipwz79qoh"/><path class="j3lsn4bia"/><path class="dc0xg9bgf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dust-storm-duotone-bold" {...props}></Icon>
<style>
:global(.aszcawbfm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 6 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dc0xg9bgf) {
  d: path("M9 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ebnbsgm1q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.idl7fxbhb) {
  d: path("m17 6 3 -3");
}

:global(.ipwz79qoh) {
  d: path("m19 11 3 -3");
}

:global(.j3lsn4bia) {
  d: path("M3 16h12");
}

:global(.jlsz29kli) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 11 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.otysgl0gj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.plajqrbag) {
  fill: currentColor;
  d: path("M9 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.timme522h) {
  d: path("M3 6h14");
}

:global(.u-xjqw_1i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vzfmp7bra) {
  d: path("M5 11h14");
}

</style>
