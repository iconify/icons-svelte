<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d8akb9mvh"/><path class="tiii5dp5x"/><path class="ko222axdi"/><path class="cg92043wk"/><path class="qo1oa5ffe"/><path class="se2rttqrj"/><path class="sa7t2q-eb"/><path class="ek6w2ymjs"/><path class="w7htkxb5b"/><path class="hh2-r7bhw"/><path class="cmb7dmbhv"/><path class="olqp5-9mh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:magnet-snap-duotone-bold" {...props}></Icon>
<style>
:global(.cg92043wk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 14a2 2 0 0 1 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cmb7dmbhv) {
  d: path("M10 3v11");
}

:global(.d8akb9mvh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 14a6 6 0 0 1 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ek6w2ymjs) {
  d: path("M6 3v11");
}

:global(.hh2-r7bhw) {
  d: path("M14 14a2 2 0 0 1 -4 0");
}

:global(.ko222axdi) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.olqp5-9mh) {
  d: path("M14 3v11");
}

:global(.qo1oa5ffe) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sa7t2q-eb) {
  d: path("M18 14a6 6 0 0 1 -12 0");
}

:global(.se2rttqrj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tiii5dp5x) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 3v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w7htkxb5b) {
  d: path("M18 3v11");
}

</style>
