<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="udw1i4tmx"/><path class="wn08sczhn"/><path class="cx_7ro3do"/><path class="ja82agbmj"/><path class="kc6uvv_9p"/><path class="jtrmczbpr"/><path class="f-x5yl3mg"/><path class="blzwzs-bz"/><path class="gyi-tobvb"/><path class="ztr6a0gki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:collation-duotone-bold" {...props}></Icon>
<style>
:global(.blzwzs-bz) {
  d: path("M2 18h8");
}

:global(.cx_7ro3do) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f-x5yl3mg) {
  d: path("M2 12h11");
}

:global(.gyi-tobvb) {
  d: path("M20 5v14");
}

:global(.ja82agbmj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jtrmczbpr) {
  d: path("M2 6h14");
}

:global(.kc6uvv_9p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 16 3 3 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.udw1i4tmx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wn08sczhn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ztr6a0gki) {
  d: path("m17 16 3 3 2 -2");
}

</style>
