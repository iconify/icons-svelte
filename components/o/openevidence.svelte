<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ap5ec8ypu"/><path class="xme7cmtwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:openevidence" {...props}></Icon>
<style>
:global(.ap5ec8ypu) {
  cx: 15.5px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 11px;
  ry: 13px;
}

:global(.xme7cmtwy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.5 37h28v-6.5M15.5 11h26v5.5M37 20v7m0-3.5h-8.5m0-12.5v26");
}

</style>
