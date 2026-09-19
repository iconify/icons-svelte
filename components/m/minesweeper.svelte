<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qjq3p05om"/><circle class="rf781kb8x"/><path class="tjy-dsbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:minesweeper" {...props}></Icon>
<style>
:global(.qjq3p05om) {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("M15.24 22.65a2.2 2.2 0 1 1 2.19-2.19a2.19 2.19 0 0 1-2.19 2.19ZM21 18.89a3 3 0 1 1 3-3a3 3 0 0 1-3 3Z");
}

:global(.rf781kb8x) {
  cx: 24.01px;
  cy: 24px;
  r: 15.73px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tjy-dsbnn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5v5.77m21.51 15.71h-5.76M24.03 45.5v-5.77M2.51 24.02h5.77m26.86-11.14l2.04-2.04m-2.04 24.28l2.04 2.04m-24.29-2.04l-2.04 2.04m2.04-24.28l-2.04-2.04");
}

</style>
