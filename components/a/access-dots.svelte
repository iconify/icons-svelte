<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="oqer3o_zd"/><circle class="nkdc8bcig"/><path class="j2aj__zre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:access-dots" {...props}></Icon>
<style>
:global(.j2aj__zre) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.501 24a19.4 19.4 0 0 0 4.295 12.193h30.408a19.45 19.45 0 0 0 0-24.386H8.796A19.4 19.4 0 0 0 4.501 24");
}

:global(.nkdc8bcig) {
  cx: 32.954px;
  cy: 24px;
  r: 6.546px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.oqer3o_zd) {
  cx: 15.046px;
  cy: 24px;
  r: 6.546px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
