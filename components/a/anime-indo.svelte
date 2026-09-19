<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hwoh15byl"/><path class="o-uvrdb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:anime-indo" {...props}></Icon>
<style>
:global(.hwoh15byl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 40.022L24 7.979M20.318 28.53l-6.634 11.492h13.269z");
}

:global(.o-uvrdb5q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.136 40.022L20.318 14.356L5.5 40.022");
}

</style>
