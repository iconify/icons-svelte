<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ta1mfsbqy"/><ellipse class="bmwai8ywp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mi-o2" {...props}></Icon>
<style>
:global(.bmwai8ywp) {
  cx: 19.816px;
  cy: 20.962px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.642px;
  ry: 15.461px;
}

:global(.ta1mfsbqy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.545 34.063a4.17 4.17 0 0 1 4.062-4.218a4.198 4.198 0 0 1 2.969 7.187c-1.719 1.406-7.03 5.468-7.03 5.468h8.28");
}

</style>
