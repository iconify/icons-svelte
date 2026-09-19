<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xhm3jthbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:everdo" {...props}></Icon>
<style>
:global(.xhm3jthbo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.07 37.76a2.25 2.25 0 0 1-3.17 0L4.5 26.37l3.17-3.17l9.81 9.8l22.85-22.84l3.17 3.17Z");
}

</style>
