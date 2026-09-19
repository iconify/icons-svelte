<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p024l5x7k"/><circle class="zm3xl_xmm"/><path class="h5e3hy6cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:myasus" {...props}></Icon>
<style>
:global(.h5e3hy6cd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.535 17.552v19.462");
}

:global(.p024l5x7k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.371 10.64h-7.545L4.5 37.36h7.545zm16.129 0h-7.545L20.629 37.36h7.545zm0 0v26.374H33.265");
}

:global(.zm3xl_xmm) {
  cx: 33.265px;
  cy: 34.324px;
  r: 2.69px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
