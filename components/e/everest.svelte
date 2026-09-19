<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iisp2qbhp"/><path class="wb5xuj0jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:everest" {...props}></Icon>
<style>
:global(.iisp2qbhp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 40.021L19.375 7.98l6.373 11.513l3.398-6.25L43.5 39.993z");
}

:global(.wb5xuj0jd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.355 34.845l7.02-15.81l6.373 9.904l3.398-6.234l6.69 12.267z");
}

</style>
