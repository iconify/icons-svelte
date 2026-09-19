<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vw0h1d_tk"/><path class="u-bjsk33z"/><circle class="lquaebcab"/><path class="tn4zrpbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kena-mobile" {...props}></Icon>
<style>
:global(.lquaebcab) {
  cx: 24px;
  cy: 13.625px;
  r: 4.277px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tn4zrpbhx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.062 6.613h6.51m16.856 0h6.51L36.825 4.5");
}

:global(.u-bjsk33z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.938 43.5a14.938 14.938 0 0 0-29.876 0");
}

:global(.vw0h1d_tk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.062 13.625a14.938 14.938 0 1 0 29.876 0");
}

</style>
