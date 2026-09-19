<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i3od64bjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:docusign" {...props}></Icon>
<style>
:global(.i3od64bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.962 20.913h9.216L24 35.02L9.822 20.913h9.216V6.497h9.924zM42.5 41.503h-37");
}

</style>
