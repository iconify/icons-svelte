<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="lovuhby4g"/><ellipse class="ithd4eb-c"/><path class="bribo1bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:blubank" {...props}></Icon>
<style>
:global(.bribo1bfa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.874 7.161v23.982");
}

:global(.ithd4eb-c) {
  cx: 24px;
  cy: 31.143px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 12.126px;
  ry: 12.357px;
}

:global(.lovuhby4g) {
  cx: 26.182px;
  cy: 6.556px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.061px;
  ry: 2.057px;
}

</style>
