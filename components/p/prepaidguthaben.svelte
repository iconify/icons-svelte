<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="fv763l4rj"/><path class="yzdo72b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:prepaidguthaben" {...props}></Icon>
<style>
:global(.fv763l4rj) {
  cx: 29.88px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.62px;
  ry: 13.633px;
}

:global(.yzdo72b6p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.12 37.633A13.626 13.626 0 0 1 4.5 24a13.626 13.626 0 0 1 13.62-13.633");
}

</style>
