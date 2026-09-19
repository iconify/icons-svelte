<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="m09l9lqnj"/><path class="sq-bkdbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:audacy" {...props}></Icon>
<style>
:global(.m09l9lqnj) {
  cx: 13.619px;
  cy: 30.071px;
  r: 9.119px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sq-bkdbxe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.668 39.27H43.5L27.152 8.73H14.08c5.781 10.018 10.71 20.355 16.588 30.54");
}

</style>
