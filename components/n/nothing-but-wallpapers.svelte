<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t7klum62q"/><path class="luh9s9b5i"/><circle class="b96bdnw7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nothing-but-wallpapers" {...props}></Icon>
<style>
:global(.b96bdnw7u) {
  cx: 34.192px;
  cy: 6.719px;
  r: 3.441px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.luh9s9b5i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.586 20.587L19.521 8.822L9.306 23.723");
}

:global(.t7klum62q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45 23.723c0 11.598-9.402 21-21 21s-21-9.403-21-21zm-6.183 0l-6.9-8.417l-6.901 8.417");
}

</style>
