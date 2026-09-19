<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="uhx3m_1tm"/><path class="jglvpbewn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:editor" {...props}></Icon>
<style>
:global(.jglvpbewn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.477 9.371h23.046m-23.046 7.314h23.046M12.477 24h23.046m-23.046 7.314h23.046m-23.046 7.315h23.046");
}

:global(.uhx3m_1tm) {
  width: 31px;
  height: 39px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
