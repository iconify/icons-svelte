<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x0j_vr2al"/><path class="w15enlbmr"/><path class="k5lmobclv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:jira" {...props}></Icon>
<style>
:global(.k5lmobclv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.972 5.5a8.736 8.736 0 0 0 8.736 8.736h2.056v2.056a8.736 8.736 0 0 0 8.736 8.736h0V5.5Z");
}

:global(.w15enlbmr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.236 14.236a8.736 8.736 0 0 0 8.736 8.736h2.056v2.056a8.736 8.736 0 0 0 8.736 8.736h0V14.236Z");
}

:global(.x0j_vr2al) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 22.972a8.736 8.736 0 0 0 8.736 8.736h2.056v2.056a8.736 8.736 0 0 0 8.736 8.736h0V22.972Z");
}

</style>
