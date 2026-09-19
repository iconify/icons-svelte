<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="tjfqwg1py"/><ellipse class="ewon5lm0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:outdooractive" {...props}></Icon>
<style>
:global(.ewon5lm0g) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.81px;
  ry: 11.691px;
}

:global(.tjfqwg1py) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 16.834px;
  ry: 19.5px;
}

</style>
