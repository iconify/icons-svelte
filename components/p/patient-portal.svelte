<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b-zvlb6hf"/><path class="aofc66r0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:patient-portal" {...props}></Icon>
<style>
:global(.aofc66r0d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.677 4.662a43.5 43.5 0 0 0-1.942 15.783m2.54 10.056a46.5 46.5 0 0 0 8.885 12.837M18.663 25.644A30.9 30.9 0 0 0 3.5 22.993");
}

:global(.b-zvlb6hf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.5 19.606C26.689 21.413 18.372 29.732 12.224 42.93");
}

</style>
