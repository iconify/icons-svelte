<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="va93cxbbs"/><path class="xr778lbyu"/><path class="l3hfq7bhw"/><path class="iyj_k-bwo"/><path class="gjmq94baq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ethernet-duotone-regular" {...props}></Icon>
<style>
:global(.gjmq94baq) {
  d: path("M15 11v4");
}

:global(.iyj_k-bwo) {
  d: path("M12 11v4");
}

:global(.l3hfq7bhw) {
  d: path("M9 11v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.va93cxbbs) {
  fill: currentColor;
  d: path("M5 8h4V4h6v4h4v12H5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xr778lbyu) {
  d: path("M5 8h4V4h6v4h4v12H5Z");
}

</style>
