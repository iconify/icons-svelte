<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fdl-f1bvu"/><path class="s1sh7sbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kmplayer" {...props}></Icon>
<style>
:global(.fdl-f1bvu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 7.473v33.054l25.472-16.568z");
}

:global(.s1sh7sbgk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.819 19.106L42.5 7.473v33.054L23.819 28.569");
}

</style>
