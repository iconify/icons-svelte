<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="apgoexbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:doodle" {...props}></Icon>
<style>
:global(.apgoexbaa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.8 4.5h8.1v39h-8.1v-1.8c-5.4 3.4-12.5 1.8-15.9-3.6s-1.8-12.5 3.6-15.9c3.7-2.4 8.5-2.4 12.2 0V4.5zm-6.1 22.7c-2.6 0-4.8 2.1-4.8 4.8s2.1 4.8 4.8 4.8s4.8-2.1 4.8-4.8c0-2.6-2.2-4.8-4.8-4.8q0 0 0 0");
}

</style>
