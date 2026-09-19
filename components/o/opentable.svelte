<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ezbbd8bjk"/><circle class="ma-3cdbxn"/><circle class="je1hsbcdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:opentable" {...props}></Icon>
<style>
:global(.ezbbd8bjk) {
  cx: 28.5px;
  cy: 24px;
  r: 15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.je1hsbcdz) {
  cx: 7.5px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ma-3cdbxn) {
  cx: 28.5px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
