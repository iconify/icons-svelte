<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="lny57n3pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:round-photo" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lny57n3pm) {
  cx: 24px;
  cy: 24px;
  r: 17.5px;
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 2.927 3.927;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
