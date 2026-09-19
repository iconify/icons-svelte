<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ojwogphoe"/><path class="l_ktaib9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gruppo-san-donato" {...props}></Icon>
<style>
:global(.l_ktaib9e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 44.289c6.18-6.18 8.512-11.759 0-20.27S17.819 9.93 24 3.749");
}

:global(.ojwogphoe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.833 24.019l.01 20.274a21.5 21.5 0 0 1 .12-40.59m14.204 20.316V3.749a21.5 21.5 0 0 1-.022 40.548");
}

</style>
