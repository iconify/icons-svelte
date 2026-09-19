<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ezn_mmi0b"/><path class="bxzy4fpvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cenobrowser" {...props}></Icon>
<style>
:global(.bxzy4fpvg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.91 18.997H25.62v10h19.29M45.5 24H25.621");
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ezn_mmi0b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.62 28.997c-2.04 5.54-7.37 9.5-13.62 9.5c-8.01 0-14.5-6.49-14.5-14.5s6.49-14.5 14.5-14.5c6.25 0 11.58 3.96 13.62 9.5");
}

</style>
