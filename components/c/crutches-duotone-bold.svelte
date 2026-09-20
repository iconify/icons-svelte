<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vk_v27wsj"/><path class="n5a0r5b3k"/><path class="g-nwz4bua"/><path class="obdsjcckp"/><path class="fey7rmb_f"/><path class="b3c3cje8u"/><path class="yfvv4yzsv"/><path class="py87sqk9l"/><path class="fa77bsbgi"/><path class="bhj229bdw"/><path class="tj33frbke"/><path class="w2atjyb_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:crutches-duotone-bold" {...props}></Icon>
<style>
:global(.b3c3cje8u) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bhj229bdw) {
  d: path("M14 4h6");
}

:global(.fa77bsbgi) {
  d: path("M4 10h6");
}

:global(.fey7rmb_f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 4v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g-nwz4bua) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n5a0r5b3k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.obdsjcckp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.py87sqk9l) {
  d: path("M7 4v17");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tj33frbke) {
  d: path("M17 4v17");
}

:global(.vk_v27wsj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w2atjyb_m) {
  d: path("M14 10h6");
}

:global(.yfvv4yzsv) {
  d: path("M4 4h6");
}

</style>
