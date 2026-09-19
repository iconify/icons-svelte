<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iok58zbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hanping-popup" {...props}></Icon>
<style>
:global(.iok58zbkv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 21.944H15.778C10.1 21.944 5.5 26.546 5.5 32.222S10.102 42.5 15.778 42.5s10.278-4.601 10.278-10.278V5.5");
}

</style>
