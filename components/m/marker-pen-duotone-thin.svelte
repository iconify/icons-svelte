<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d_ck1z3vq"/><path class="nbr-9yb3l"/><path class="yigkywbyn"/><path class="ry5l7ebuo"/><path class="ot37jibbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:marker-pen-duotone-thin" {...props}></Icon>
<style>
:global(.d_ck1z3vq) {
  fill: currentColor;
  d: path("m8 14 8 -8 4 4 -8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nbr-9yb3l) {
  fill: currentColor;
  d: path("m5 17 3 -3 4 4 -3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ot37jibbb) {
  d: path("m10 16 4 -4");
}

:global(.ry5l7ebuo) {
  d: path("m5 17 3 -3 4 4 -3 3Z");
}

:global(.yigkywbyn) {
  d: path("m8 14 8 -8 4 4 -8 8Z");
}

</style>
