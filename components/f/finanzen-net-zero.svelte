<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ygz7-09gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:finanzen-net-zero" {...props}></Icon>
<style>
:global(.ygz7-09gl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 21.5v13c0 4.432-3.568 8-8 8h-21c-4.432 0-8-3.568-8-8l37-21c0-4.432-3.568-8-8-8h-21c-4.432 0-8 3.568-8 8v13");
}

</style>
