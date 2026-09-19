<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r50vthbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mclaren" {...props}></Icon>
<style>
:global(.r50vthbgp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 24.817C37.16 7.22 62.037 9.58 25.155 34.6c2.963-3.163 5.443-7.633 2.611-10.778c-2.322-3.185-13.1-3.138-23.266.996z");
}

</style>
