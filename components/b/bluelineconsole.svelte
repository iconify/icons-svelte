<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mmx9xl-me"/><path class="kberpgbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bluelineconsole" {...props}></Icon>
<style>
:global(.kberpgbwh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.21 22.74l5.64 5.46l-5.64 5.46");
}

:global(.mmx9xl-me) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 19.2h39v18h-39zm0 0v-8.4h16l6.9 8.4");
}

</style>
