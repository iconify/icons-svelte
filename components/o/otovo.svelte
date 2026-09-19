<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wwodwyb6k"/><ellipse class="hbdeh7bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:otovo" {...props}></Icon>
<style>
:global(.hbdeh7bww) {
  cx: 11.5px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9px;
  ry: 9.5px;
}

:global(.wwodwyb6k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 33.214V45.5m0-43v12.286m15.203-5.989l-8.687 8.688M45.5 24H33.214m5.989 15.203l-8.687-8.687");
}

</style>
