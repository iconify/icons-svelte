<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lkj-yhqhw"/><circle class="mx3lq6d4u"/><path class="cxql20buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:logcatreader" {...props}></Icon>
<style>
:global(.cxql20buf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.664 25.498l6.002 6.002");
}

:global(.lkj-yhqhw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.5v35a2 2 0 0 0 2 2h2.33v-39H10.4a2 2 0 0 0-2 2m4.331-2v39h24.87a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

:global(.mx3lq6d4u) {
  cx: 23.937px;
  cy: 21.771px;
  r: 5.271px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
