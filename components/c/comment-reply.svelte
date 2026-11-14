<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k9_4tgb1k"/><path class="umf7udl4c"/><path class="gk_cikbbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:comment-reply" {...props}></Icon>
<style>
:global(.gk_cikbbr) {
  d: path("M10.75 9.25L8.5 11.5l2.25 2.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k9_4tgb1k) {
  d: path("m7.5 19.5l-3.5 1L5 17a8.5 8.5 0 1 1 2.5 2.5");
}

:global(.umf7udl4c) {
  d: path("M15.5 15v-1a2.5 2.5 0 0 0-2.5-2.5H8.5");
}

</style>
