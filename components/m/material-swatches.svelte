<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wutk-mbkx"/><path class="hk_w-62jb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:material-swatches" {...props}></Icon>
<style>
:global(.hk_w-62jb) {
  d: path("M13 9.5h5a3.5 3.5 0 0 1 3.5 3.5v5a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 9.5 18v-5A3.5 3.5 0 0 1 13 9.5m-10.5-3h12m-5 11h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wutk-mbkx) {
  d: path("M9.5 14.5h-5a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v5");
}

</style>
