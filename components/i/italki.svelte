<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jdp6r-d-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:italki" {...props}></Icon>
<style>
:global(.jdp6r-d-e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 16.5v15a2 2 0 0 0 2 2h28l5 6v-6h2a2 2 0 0 0 2-2v-15a2 2 0 0 0-2-2h-35a2 2 0 0 0-2 2");
}

</style>
