<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wn08sczhn"/><path class="g8cnfwuqc"/><path class="h-5zvjt1d"/><path class="sum5xgbhm"/><path class="f-x5yl3mg"/><path class="usiycnb-x"/><path class="hwv-lccbz"/><path class="xyhj-ubbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:parser-duotone-bold" {...props}></Icon>
<style>
:global(.f-x5yl3mg) {
  d: path("M2 12h11");
}

:global(.g8cnfwuqc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h-5zvjt1d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 7h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hwv-lccbz) {
  d: path("M13 7h7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sum5xgbhm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.usiycnb-x) {
  d: path("M13 7v10");
}

:global(.wn08sczhn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xyhj-ubbr) {
  d: path("M13 17h7");
}

</style>
