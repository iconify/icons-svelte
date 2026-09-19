<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="huq2su-yu"/><circle class="gmxt364bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:curiositystream" {...props}></Icon>
<style>
:global(.gmxt364bx) {
  cx: 24px;
  cy: 40.23px;
  r: 3.34px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.huq2su-yu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.8 4.58v16a9.2 9.2 0 0 0 18.4 0v-16M24 33.86v-4.09");
}

</style>
