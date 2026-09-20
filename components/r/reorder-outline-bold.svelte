<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sxy07wbdf"/><path class="eu9kkgbdm"/><path class="x3jqftbaj"/><path class="r3faxubne"/><path class="weza57brb"/><path class="al6h6yb3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reorder-outline-bold" {...props}></Icon>
<style>
:global(.al6h6yb3y) {
  d: path("m2 18 2 2 2 -2");
}

:global(.eu9kkgbdm) {
  d: path("M9 12h12");
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

:global(.sxy07wbdf) {
  d: path("M9 7h12");
}

:global(.weza57brb) {
  d: path("m2 6 2 -2 2 2");
}

:global(.x3jqftbaj) {
  d: path("M9 17h12");
}

</style>
