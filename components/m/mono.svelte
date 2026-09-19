<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iy2zvecgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mono" {...props}></Icon>
<style>
:global(.iy2zvecgi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5A9.25 9.25 0 0 0 24 24ZM24 24a9.25 9.25 0 0 1 0-18.5Zm18.5 0A9.25 9.25 0 0 0 24 24ZM24 24a9.25 9.25 0 0 1-18.5 0Z");
}

</style>
