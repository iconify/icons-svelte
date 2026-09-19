<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="n-_pwbbkt"/><path class="m52jk0bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gotrendier" {...props}></Icon>
<style>
:global(.m52jk0bod) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.706 19.5a9 9 0 1 1 .08 9.135l-5.572-9.27");
}

:global(.n-_pwbbkt) {
  cx: 13.5px;
  cy: 24px;
  r: 9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
