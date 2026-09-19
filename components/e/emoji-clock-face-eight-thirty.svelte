<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="osh9rgbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emoji-clock-face-eight-thirty" {...props}></Icon>
<style>
:global(.osh9rgbrm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.04 24.068v15.89m-.015-15.914l-9.348 5.396M2.5 24c-.001 11.873 9.624 21.499 21.498 21.5s21.5-9.623 21.502-21.495V24c.001-11.873-9.624-21.499-21.498-21.5S2.502 12.123 2.5 23.996z");
}

</style>
