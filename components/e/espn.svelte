<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n0y_2pmko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:espn" {...props}></Icon>
<style>
:global(.n0y_2pmko) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.044 5.825L8.746 16.283l32.456-.072L42.5 5.825zM8.421 19.78L5.5 42.176h32.456l.974-9.736H18.807l.65-4.22h20.122l1.298-8.438z");
}

</style>
