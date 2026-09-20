<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="laxlotbrr"/><path class="t08snsqkg"/><path class="isrhyfbxd"/><path class="qjgj-fbph"/><path class="d-qcdbb2z"/><path class="y-vga5bbj"/><path class="uilxv67me"/><path class="isrkj8blm"/><path class="bvj__8b4y"/><path class="rrc90qj9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-flat-duotone-bold" {...props}></Icon>
<style>
:global(.bvj__8b4y) {
  d: path("M20 4v11");
}

:global(.d-qcdbb2z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 13 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.isrhyfbxd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.isrkj8blm) {
  d: path("M3 17h13");
}

:global(.laxlotbrr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qjgj-fbph) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 4v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rrc90qj9p) {
  d: path("m18 13 2 2 2 -2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t08snsqkg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uilxv67me) {
  d: path("M3 11h13");
}

:global(.y-vga5bbj) {
  d: path("M3 5h13");
}

</style>
