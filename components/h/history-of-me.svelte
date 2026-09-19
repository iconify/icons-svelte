<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="b72o4ccfw"/><circle class="peh688b2w"/><circle class="jtq14ibpo"/><path class="lkkes6b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:history-of-me" {...props}></Icon>
<style>
:global(.b72o4ccfw) {
  cx: 18.332px;
  cy: 15.02px;
  r: 5.389px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jtq14ibpo) {
  cx: 24.056px;
  cy: 9.889px;
  r: 5.389px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lkkes6b-o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.056 11.267V43.5m0-9.298h-4.422m4.422 2.935h-4.422m4.422 2.89h-4.422");
}

:global(.peh688b2w) {
  cx: 29.668px;
  cy: 15.02px;
  r: 5.389px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
