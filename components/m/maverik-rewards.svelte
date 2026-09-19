<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rj8ze1h0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:maverik-rewards" {...props}></Icon>
<style>
:global(.rj8ze1h0j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.9 37.51L16.2 17.245L4.5 37.51h39L27.9 10.49L12.3 37.51");
}

</style>
