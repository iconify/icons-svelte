<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="d1iyv0blr"/><circle class="iduej5bfj"/><circle class="aj5p9tbck"/><circle class="kf6-t6vzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dots" {...props}></Icon>
<style>
:global(.aj5p9tbck) {
  cx: 34.5px;
  cy: 13.5px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.d1iyv0blr) {
  cx: 13.5px;
  cy: 13.5px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.iduej5bfj) {
  cx: 34.5px;
  cy: 34.5px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.kf6-t6vzx) {
  cx: 13.5px;
  cy: 34.5px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
