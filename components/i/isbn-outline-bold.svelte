<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qltxbpdvm"/><path class="tr_jskylo"/><path class="z3it7clmt"/><path class="leemd3bqp"/><path class="h9fb_9biv"/><path class="oifr9zbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:isbn-outline-bold" {...props}></Icon>
<style>
:global(.h9fb_9biv) {
  d: path("M20 5v12");
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

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tr_jskylo) {
  d: path("M7 5v12");
}

:global(.z3it7clmt) {
  d: path("M11 5v12");
}

</style>
