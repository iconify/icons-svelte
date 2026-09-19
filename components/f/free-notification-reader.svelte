<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o6f1dzbqb"/><path class="me6vf2bfe"/><circle class="t4b659o-m"/><path class="sino8-bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:free-notification-reader" {...props}></Icon>
<style>
:global(.me6vf2bfe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.69 17.309a1.5 1.5 0 0 1-1.5-1.5c0-.397.158-.755.41-1.024c-.116-.016-.23-.035-.35-.035a2.5 2.5 0 1 0 2.5 2.5c0-.12-.02-.234-.035-.35a1.5 1.5 0 0 1-1.024.409Z");
}

:global(.o6f1dzbqb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24M24 2.5v43M45.5 24h-43");
}

:global(.sino8-bhk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 35.056c6.106 0 11.056-4.95 11.056-11.056");
}

:global(.t4b659o-m) {
  cx: 24px;
  cy: 24px;
  r: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
