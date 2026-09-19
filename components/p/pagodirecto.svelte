<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="u1r89jbky"/><path class="osb08rrfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pagodirecto" {...props}></Icon>
<style>
:global(.osb08rrfe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.714 14.649V4.5l2.205 1.24l2.205-1.24V24m-19.838 9.351V43.5l-2.205-1.24l-2.205 1.24V24");
}

:global(.u1r89jbky) {
  cx: 24px;
  cy: 24px;
  r: 12.124px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
