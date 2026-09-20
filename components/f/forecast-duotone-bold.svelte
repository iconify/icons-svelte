<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="z6pxoelda"/><path class="ikmlgdrhd"/><path class="gk0fd-2dg"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="y09n-7bbz"/><path class="xjxf-fbjv"/><path class="z0_yphh3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:forecast-duotone-bold" {...props}></Icon>
<style>
:global(.dh-nlhghu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gk0fd-2dg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 5 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ikmlgdrhd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 9 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xjxf-fbjv) {
  d: path("m13 9 2 -2");
}

:global(.y09n-7bbz) {
  d: path("m6 16 5 -5");
}

:global(.z0_yphh3l) {
  d: path("m17 5 2 -2");
}

:global(.z6pxoelda) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 16 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
