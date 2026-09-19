<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n3izh9rmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fortuno" {...props}></Icon>
<style>
:global(.n3izh9rmm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24c0 10.217-8.283 18.5-18.5 18.5S5.5 34.217 5.5 24S13.783 5.5 24 5.5h18.5z");
}

</style>
