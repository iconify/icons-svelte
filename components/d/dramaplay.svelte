<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d1wno8k_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dramaplay" {...props}></Icon>
<style>
:global(.d1wno8k_f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.75 24H14a8.5 8.5 0 1 0 8.5 8.5V7m6.75 17H34a8.5 8.5 0 1 0-8.5-8.5V41");
}

</style>
