<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l5dlw1yel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bp-pro" {...props}></Icon>
<style>
:global(.l5dlw1yel) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.817 5.5L5.698 16.015V42.5h26.485l10.119-10.515V5.5zM5.698 24.87h15.14m-7.57-7.57v15.14M23.447 17.3l11.799 15.14m0-15.14L23.447 32.44");
}

</style>
