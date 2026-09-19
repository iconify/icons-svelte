<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z2-gtrb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:property-finder" {...props}></Icon>
<style>
:global(.z2-gtrb0x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 30.5c0-7.18-5.82-13-13-13c0-7.18 5.82-13 13-13s13 5.82 13 13s-5.82 13-13 13H11v13c7.18 0 13-5.82 13-13");
}

</style>
