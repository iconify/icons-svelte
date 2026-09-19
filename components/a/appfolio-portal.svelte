<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dvfjoxrhm"/><circle class="m--thhb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:appfolio-portal" {...props}></Icon>
<style>
:global(.dvfjoxrhm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.322 43.5l-16.494-2.519V7.912L29.322 4.5zm0-35.912h5.85v33.8");
}

:global(.m--thhb8j) {
  cx: 25.584px;
  cy: 26.173px;
  r: 1.503px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
