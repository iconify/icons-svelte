<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ocjulabft"/><path class="p5796tbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:quora" {...props}></Icon>
<style>
:global(.ocjulabft) {
  cx: 24px;
  cy: 24px;
  r: 13.6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.p5796tbhb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.6 37.6l4.3 4.6c.4.4.6.8.6 1.4c0 1.1-.9 1.9-1.9 1.9H24C12.1 45.5 2.5 35.9 2.5 24S12.1 2.5 24 2.5S45.5 12.1 45.5 24c0 5.2-1.8 9.9-4.9 13.6");
}

</style>
