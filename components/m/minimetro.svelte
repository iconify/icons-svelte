<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="f08ezs4lq"/><path class="lw6wdebmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:minimetro" {...props}></Icon>
<style>
:global(.f08ezs4lq) {
  cx: 23.5px;
  cy: 24px;
  r: 14.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lw6wdebmr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.5 9.5v-5m0 39v-5m6-27.7V4.5m-12 6.3V4.5m16.25 29.75L39 39.5m-10.06-2.06l5.54 5.54");
}

</style>
