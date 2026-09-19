<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mlpudrl4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bmeia" {...props}></Icon>
<style>
:global(.mlpudrl4j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.3h39v7.8H8.4Zm7.8 15.6h31.2v7.8H16.2Z");
}

</style>
