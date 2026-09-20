<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qi0on19bi"/><path class="fhtkkzo7b"/><path class="ipg5ngbqc"/><path class="ghgpbwtop"/><path class="prj9u5frn"/><path class="fdrffh_te"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:remote-control-duotone-bold" {...props}></Icon>
<style>
:global(.fdrffh_te) {
  d: path("M9 13h5");
}

:global(.fhtkkzo7b) {
  fill: currentColor;
  d: path("M11 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ghgpbwtop) {
  d: path("M11 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ipg5ngbqc) {
  d: path("M7 2v20h10V2Z");
}

:global(.prj9u5frn) {
  d: path("M9 10h5");
}

:global(.qi0on19bi) {
  fill: currentColor;
  d: path("M7 2v20h10V2Z");
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

</style>
