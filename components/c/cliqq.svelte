<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="okenx4bsj"/><circle class="wcfxh0jbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cliqq" {...props}></Icon>
<style>
:global(.okenx4bsj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.759 43.5L24.241 30.982M11.24 30.5c0 7.222 5.779 13 12.52 13c7.221 0 13-5.778 13-13v-13c0-7.222-5.779-13-13-13s-12.52 5.778-12.52 13z");
}

:global(.wcfxh0jbd) {
  cx: 24px;
  cy: 24px;
  r: 3.225px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
