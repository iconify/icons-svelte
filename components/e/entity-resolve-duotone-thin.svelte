<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zxrob3sge"/><path class="jz9jnbbik"/><path class="i8o-y7bnj"/><path class="dfcdzc65k"/><path class="aeyekmbly"/><path class="pxp27mb9k"/><path class="ks612kq_w"/><path class="kiksj5oln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:entity-resolve-duotone-thin" {...props}></Icon>
<style>
:global(.aeyekmbly) {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dfcdzc65k) {
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i8o-y7bnj) {
  fill: currentColor;
  d: path("M12 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jz9jnbbik) {
  fill: currentColor;
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kiksj5oln) {
  d: path("M12 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.ks612kq_w) {
  d: path("m7 17 5 -5");
}

:global(.pxp27mb9k) {
  d: path("m7 7 5 5");
}

:global(.zxrob3sge) {
  fill: currentColor;
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
