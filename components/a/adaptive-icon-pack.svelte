<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="xav3-zbdm"/><circle class="t238zrbfy"/><path class="zjc0elbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:adaptive-icon-pack" {...props}></Icon>
<style>
:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.t238zrbfy) {
  cx: 24px;
  cy: 24px;
  r: 13px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xav3-zbdm) {
  cx: 24px;
  cy: 24px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zjc0elbpl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.192 14.808l8.136-8.136M6.671 41.328l8.137-8.136");
}

</style>
