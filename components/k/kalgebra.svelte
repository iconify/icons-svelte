<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t7z_u__wt"/><path class="lvlugq24t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kalgebra" {...props}></Icon>
<style>
:global(.lvlugq24t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2.006 2.006 0 0 1-2-2v-9h-18a2.006 2.006 0 0 0-2 2v35a2.006 2.006 0 0 0 2 2h27a2.006 2.006 0 0 0 2-2Zm-11-11l11 11");
}

:global(.t7z_u__wt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.324 34.456h-8.657l4.333-6.5l-4.32-6.5h8.653");
}

</style>
