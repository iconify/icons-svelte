<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="twp5c8mgm"/><path class="iv55jvbip"/><path class="facaoccxd"/><path class="c4khiwgvb"/><path class="wv_9g9b3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:birthday-candle-duotone-bold" {...props}></Icon>
<style>
:global(.c4khiwgvb) {
  d: path("M8 15h8");
}

:global(.facaoccxd) {
  d: path("M8 21V11h8v10Z");
}

:global(.iv55jvbip) {
  fill: currentColor;
  d: path("M12 9c-2.5 -2 -2.5 -5 0 -7 2.5 2 2.5 5 0 7");
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

:global(.twp5c8mgm) {
  fill: currentColor;
  d: path("M8 21V11h8v10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wv_9g9b3l) {
  d: path("M12 9c-2.5 -2 -2.5 -5 0 -7 2.5 2 2.5 5 0 7");
}

</style>
