<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="l3vagbb4b"/><path class="nc5br2wvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:onetouch" {...props}></Icon>
<style>
:global(.l3vagbb4b) {
  cx: 28.593px;
  cy: 19.183px;
  r: 13.052px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.nc5br2wvf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.645 23.746c1.859 9.807 9.578 17.526 19.385 19.384");
}

</style>
