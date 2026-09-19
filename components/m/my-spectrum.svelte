<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qpgc8sblw"/><circle class="chdt74bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:my-spectrum" {...props}></Icon>
<style>
:global(.chdt74bhh) {
  cx: 24.412px;
  cy: 15.074px;
  r: 9.574px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.qpgc8sblw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.865 42.5c0-9.867-7.998-17.865-17.865-17.865S6.135 32.633 6.135 42.5z");
}

</style>
