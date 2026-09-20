<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t7gbc3iwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fanfiction-net" {...props}></Icon>
<style>
:global(.t7gbc3iwp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h27a10 10 0 0 1 10 10v27h-27a10 10 0 0 1-10-10zm0 18.5h37");
}

</style>
