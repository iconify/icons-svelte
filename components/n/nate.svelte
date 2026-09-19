<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ybuwyomsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nate" {...props}></Icon>
<style>
:global(.ybuwyomsv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.4 24v17.267h11.1V21.533q0-14.8-14.8-14.8H5.5v34.534h11.1V17.833h8.633q6.167 0 6.167 6.167");
}

</style>
