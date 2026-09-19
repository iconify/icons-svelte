<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dpnzz-44k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nissay" {...props}></Icon>
<style>
:global(.dpnzz-44k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.75 13.25L45.5 24L24 45.5L2.5 24L24 2.5zv21.5l-15.357-6.143l-6.143 6.143v-21.5l15.357 6.143z");
}

</style>
