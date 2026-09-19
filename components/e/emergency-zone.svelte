<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mx-fwobrx"/><circle class="spmelybnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emergency-zone" {...props}></Icon>
<style>
:global(.mx-fwobrx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 39.284h6.324m4.217 0H43.5m-32.676 0L17.15 8.716h13.7m1.022 4.94l5.303 25.627M24.527 13.657v15.355");
}

:global(.spmelybnm) {
  cx: 24.527px;
  cy: 32.965px;
  r: 0.75px;
  fill: currentColor;
}

</style>
