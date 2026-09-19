<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="p4od-tbho"/><path class="f8rzhmbeo"/><path class="ujfkhtbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:openlauncher" {...props}></Icon>
<style>
:global(.f8rzhmbeo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4h0a4 4 0 0 1-4 4h-25");
}

:global(.p4od-tbho) {
  width: 37px;
  height: 8px;
  x: 5.5px;
  y: 34.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
}

:global(.ujfkhtbqn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 38.5v-29a4 4 0 0 1 4-4h0a4 4 0 0 1 4 4v25");
}

</style>
