<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ewjx2zb7l"/><path class="ktq94y3-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:alphapolis" {...props}></Icon>
<style>
:global(.ewjx2zb7l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.565 17.542C-8.049 45.737 22.595 34.425 43.2 21.824");
}

:global(.ktq94y3-l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.839 39.499c22.126-58.422 27.511-19.977 26.913 0");
}

</style>
