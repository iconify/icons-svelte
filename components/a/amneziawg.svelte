<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="svwfz0hvg"/><path class="vscw7jbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:amneziawg" {...props}></Icon>
<style>
:global(.svwfz0hvg) {
  cx: 24px;
  cy: 23px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 18.5px;
  ry: 16.5px;
}

:global(.vscw7jbiu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.5 6.5l-10.878 35L24 22l-4.622 19.5L8.5 6.5");
}

</style>
