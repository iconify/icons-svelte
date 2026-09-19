<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="tpufq7bru"/><path class="romfa263c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fotmob" {...props}></Icon>
<style>
:global(.romfa263c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.991 35.989v5.297M43.5 6.714H19.991v16.959m7.786 5.006L6.971 39.039M4.5 31.462l21.197-6.135");
}

:global(.tpufq7bru) {
  cx: 31.746px;
  cy: 23.887px;
  r: 6.223px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
