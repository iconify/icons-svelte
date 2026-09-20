<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aep_ellef"/><path class="pgbf9pb9k"/><path class="wg0msbcne"/><path class="suyrjy97r"/><path class="ftqzjnb8u"/><path class="tkvxdludj"/><path class="k58vknb8e"/><path class="a1go-lhea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-failed-duotone-bold" {...props}></Icon>
<style>
:global(.a1go-lhea) {
  d: path("m21 13 -5 5");
}

:global(.aep_ellef) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.k58vknb8e) {
  d: path("m16 13 5 5");
}

:global(.pgbf9pb9k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 3h9l-3 3 3 3H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.suyrjy97r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m21 13 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tkvxdludj) {
  d: path("M6 3h9l-3 3 3 3H6");
}

:global(.wg0msbcne) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 13 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
