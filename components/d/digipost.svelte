<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="db3ytvpeg"/><path class="c98352bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:digipost" {...props}></Icon>
<style>
:global(.c98352bmu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.366 15.517h31m-5.838 0l-15-7.676l-4.059 7.676m3.132 6.618h12.397v4.632H18.601zm1.809 2.316h6.397");
}

:global(.db3ytvpeg) {
  width: 31px;
  height: 39px;
  x: 9.366px;
  y: 5.106px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
