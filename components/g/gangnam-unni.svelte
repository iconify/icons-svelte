<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mr8jy9bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gangnam-unni" {...props}></Icon>
<style>
:global(.mr8jy9bkr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 33.25a9.25 9.25 0 0 1-18.5 0V24h-9.25a9.25 9.25 0 0 1 0-18.5H42.5zM8.21 21.291l18.5 18.5");
}

</style>
