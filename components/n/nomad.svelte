<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vumq93xgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nomad" {...props}></Icon>
<style>
:global(.vumq93xgc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 38.92V8.415l37 30.505V8.415M17.815 5.642V15M30.15 32v10.358M17.695 22.5v19.858M30.137 5.642V25");
}

</style>
