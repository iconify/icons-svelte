<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="oe8unhbgc"/><path class="dgvjne8gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:figma" {...props}></Icon>
<style>
:global(.dgvjne8gv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 30.5A6.5 6.5 0 1 0 24 37v-6.5zm13-13a6.5 6.5 0 1 0 0-13H24v13zm-13-13a6.5 6.5 0 1 0 0 13H24v-13zm0 13a6.5 6.5 0 1 0 0 13H24v-13z");
}

:global(.oe8unhbgc) {
  cx: 30.5px;
  cy: 24px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
