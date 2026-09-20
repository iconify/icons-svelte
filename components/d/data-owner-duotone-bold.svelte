<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="atbcai_gj"/><path class="unova7b3b"/><path class="ejuwxub1t"/><path class="xlo0hdbks"/><path class="olmwgycdy"/><path class="ptw-mzbbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:data-owner-duotone-bold" {...props}></Icon>
<style>
:global(.atbcai_gj) {
  fill: currentColor;
  d: path("M3 5a5 2.5 0 0 1 10 0v8a5 2.5 0 0 1 -10 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ejuwxub1t) {
  d: path("M3 5a5 2.5 0 0 1 10 0v8a5 2.5 0 0 1 -10 0Z");
}

:global(.olmwgycdy) {
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ptw-mzbbd) {
  d: path("M13 21a4 4 0 0 1 8 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.unova7b3b) {
  fill: currentColor;
  d: path("M15 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xlo0hdbks) {
  d: path("M3 5a5 2.5 0 0 0 10 0");
}

</style>
