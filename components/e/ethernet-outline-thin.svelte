<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xr778lbyu"/><path class="l3hfq7bhw"/><path class="iyj_k-bwo"/><path class="gjmq94baq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ethernet-outline-thin" {...props}></Icon>
<style>
:global(.gjmq94baq) {
  d: path("M15 11v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iyj_k-bwo) {
  d: path("M12 11v4");
}

:global(.l3hfq7bhw) {
  d: path("M9 11v4");
}

:global(.xr778lbyu) {
  d: path("M5 8h4V4h6v4h4v12H5Z");
}

</style>
