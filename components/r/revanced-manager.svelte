<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="na9rivb1k"/><path class="horwmmb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:revanced-manager" {...props}></Icon>
<style>
:global(.horwmmb2o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.316 4.5l-16.376 39l-16.256-39");
}

:global(.na9rivb1k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.386 4.5h21.109L23.94 27.241Z");
}

</style>
