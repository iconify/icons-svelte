<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fxht5abwr"/><path class="i9clfwm2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dicer" {...props}></Icon>
<style>
:global(.fxht5abwr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.82 10.5a3.32 3.32 0 1 1 0 6.64a3.32 3.32 0 0 1 0-6.64m20.36 0a3.32 3.32 0 1 1 0 6.64a3.32 3.32 0 0 1 0-6.64M24 20.68a3.32 3.32 0 0 1 0 6.64a3.32 3.32 0 0 1 0-6.64M13.82 30.86a3.32 3.32 0 0 1 0 6.64a3.32 3.32 0 0 1 0-6.64m20.36 0a3.32 3.32 0 0 1 0 6.64a3.32 3.32 0 0 1 0-6.64");
}

:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
