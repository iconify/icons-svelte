<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vjl662egj"/><path class="ur---tbrc"/><path class="s75-7866b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cluster-vr" {...props}></Icon>
<style>
:global(.s75-7866b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.992 22.927a1.516 1.516 0 0 1-2.143 2.144l-1.072-1.072l1.072-1.072a1.516 1.516 0 0 1 2.143 0");
}

:global(.ur---tbrc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.63 21.427L25.201 24l-2.573 2.572l4.287 4.287l2.573-2.572l1.072 1.072a7.579 7.579 0 1 0 0-10.718l-1.072 1.072l-2.572-2.573z");
}

:global(.vjl662egj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.202 32.574a12.126 12.126 0 1 1 0-17.148l-4.287 4.287a6.063 6.063 0 1 0 0 8.575z");
}

</style>
