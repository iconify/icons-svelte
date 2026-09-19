<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="g2hh5jccm"/><path class="snhuimo5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:consorsbank-secureplus" {...props}></Icon>
<style>
:global(.g2hh5jccm) {
  width: 33.231px;
  height: 25.727px;
  x: 7.384px;
  y: 17.773px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.316px;
}

:global(.snhuimo5s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.352 17.773V15.16a10.66 10.66 0 0 1 21.32 0v2.613M24 34.636v-8");
}

</style>
