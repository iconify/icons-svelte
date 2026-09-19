<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="mbc5-pbdm"/><path class="xj46vxb9a"/><path class="fk2t6wttr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:citroen" {...props}></Icon>
<style>
:global(.fk2t6wttr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.794 33.808L24 23.23l14.206 10.576");
}

:global(.mbc5-pbdm) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 16.177px;
  ry: 20.5px;
}

:global(.xj46vxb9a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.919 26.227L24 14.254l16.082 11.973");
}

</style>
