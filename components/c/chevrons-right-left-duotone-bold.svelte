<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vn7lxkbsw"/><path class="km3c98byo"/><path class="h_ozghejt"/><path class="e_z28zb4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-right-left-duotone-bold" {...props}></Icon>
<style>
:global(.e_z28zb4o) {
  d: path("m20 7 -5 5 5 5");
}

:global(.h_ozghejt) {
  d: path("m4 7 5 5 -5 5");
}

:global(.km3c98byo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20 7 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vn7lxkbsw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
