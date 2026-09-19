<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dca9t9blb"/><path class="v4gol3bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:iof" {...props}></Icon>
<style>
:global(.dca9t9blb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.7 4.5h-2.3c-1.1 0-2 .9-2 2v35c0 1.1.9 2 2 2h2.3m0-39v39h24.9c1.1 0 2-.9 2-2v-35c0-1.1-.9-2-2-2z");
}

:global(.v4gol3bcm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.179 4.5v13.337l-3-4.385l-3 4.385V4.5");
}

</style>
