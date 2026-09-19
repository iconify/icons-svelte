<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ecvongb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:duorem" {...props}></Icon>
<style>
:global(.ecvongb1x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.39 22L23.92 4.5l17.62 17.62Zm.01 3.88h35.2L24 43.5Z");
}

</style>
