<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ar53hybyw"/><path class="tc8fh3off"/><path class="lpi5lkbmw"/><path class="bp52f-cpd"/><path class="wr9epib_z"/><path class="r2-193ooz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:grpc-duotone-bold" {...props}></Icon>
<style>
:global(.ar53hybyw) {
  fill: currentColor;
  d: path("M14 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.bp52f-cpd) {
  d: path("m11 6 3 3 -3 3");
}

:global(.lpi5lkbmw) {
  d: path("M2 9h12");
}

:global(.r2-193ooz) {
  d: path("m5 12 -3 3 3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tc8fh3off) {
  d: path("M14 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.wr9epib_z) {
  d: path("M2 15h12");
}

</style>
