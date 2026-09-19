<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p-zton0gg"/><path class="imi7g-bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:edge" {...props}></Icon>
<style>
:global(.imi7g-bld) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.204H9.895L4.5 21.732h14.105z");
}

:global(.p-zton0gg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.537 9.741l-5.192 15.906H10.098L4.5 42.796h28.209L43.5 9.741z");
}

</style>
