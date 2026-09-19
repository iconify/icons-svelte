<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vk2s7wbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mymail" {...props}></Icon>
<style>
:global(.vk2s7wbpi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.16 20.22L24 26.05L4.5 18.22v-5A3.68 3.68 0 0 1 8.17 9.5h31.66a3.68 3.68 0 0 1 3.67 3.67v21.66a3.68 3.68 0 0 1-3.67 3.67H8.17a3.68 3.68 0 0 1-3.67-3.67v-8.78");
}

</style>
