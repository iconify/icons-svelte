<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k8o0evbjv"/><path class="siptj7bkm"/><path class="wmxz4qwlq"/><path class="r95piebwx"/><path class="xmd8xmx6p"/><path class="jiw8u-asa"/><path class="qltxbpdvm"/><path class="tr_jskylo"/><path class="z3it7clmt"/><path class="leemd3bqp"/><path class="h9fb_9biv"/><path class="oifr9zbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:isbn-duotone-bold" {...props}></Icon>
<style>
:global(.h9fb_9biv) {
  d: path("M20 5v12");
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k8o0evbjv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.leemd3bqp) {
  d: path("M15 5v12");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.qltxbpdvm) {
  d: path("M4 5v12");
}

:global(.r95piebwx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.siptj7bkm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tr_jskylo) {
  d: path("M7 5v12");
}

:global(.wmxz4qwlq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xmd8xmx6p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z3it7clmt) {
  d: path("M11 5v12");
}

</style>
