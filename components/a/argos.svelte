<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e_xbsubco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:argos" {...props}></Icon>
<style>
:global(.e_xbsubco) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.071 25.966H17.829m-3.527 10.633L24.95 4.5l10.649 32.099M9.383 39.664c9.664 4.925 19.405 5.258 29.235.124");
}

</style>
