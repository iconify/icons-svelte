<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c23pli_oz"/><path class="fztiq44oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:polygon" {...props}></Icon>
<style>
:global(.c23pli_oz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5v13h13zm0 0v13H11zm0 26v-13H11zm0 13v-13H11zm0-13v-13h13z");
}

:global(.fztiq44oj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 17.5v13h13z");
}

</style>
