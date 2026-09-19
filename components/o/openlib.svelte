<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iqz1plbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:openlib" {...props}></Icon>
<style>
:global(.iqz1plbld) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.4 5v14.25l3.2-4.222l3.2 4.222V5M12 43h24a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4H12a4 4 0 0 0-4 4v30a4 4 0 0 0 4 4");
}

</style>
