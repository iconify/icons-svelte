<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nojgvvblu"/><path class="xnz1ibg2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dashwallet" {...props}></Icon>
<style>
:global(.nojgvvblu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.85 41.434l1.408-9.362h15.035c4.137 0 6.845-7.443 6.845-11.218s-3.06-4.926-6.835-4.926H13.721l1.418-9.362h11.164c8.946 0 16.197 5.332 16.197 14.288c0 8.946-7.25 20.58-16.207 20.58z");
}

:global(.xnz1ibg2v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 27.519h13.926l1.066-7.038H6.556z");
}

</style>
