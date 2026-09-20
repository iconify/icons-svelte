<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s6795lb_y"/><path class="lgw6hdcbc"/><path class="g1lzf8brc"/><path class="wlpa9-b1f"/><path class="pzm21jb5s"/><path class="fcnh_acnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flood-duotone-regular" {...props}></Icon>
<style>
:global(.fcnh_acnz) {
  d: path("m3 19 2.5 -2.5L8 19l2.5 -2.5L13 19l2.5 -2.5L18 19l2.5 -2.5");
}

:global(.g1lzf8brc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 19 2.5 -2.5L8 19l2.5 -2.5L13 19l2.5 -2.5L18 19l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lgw6hdcbc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 11v5h10v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pzm21jb5s) {
  d: path("M7 11v5h10v-5");
}

:global(.s6795lb_y) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 11 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wlpa9-b1f) {
  d: path("m5 11 7 -7 7 7");
}

</style>
