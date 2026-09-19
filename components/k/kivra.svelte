<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fg0yr9bfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kivra" {...props}></Icon>
<style>
:global(.fg0yr9bfh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.54 42.5v-37m21.793.07L7.257 23.05S23.453 46.315 41.46 41.772");
}

</style>
