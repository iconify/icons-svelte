<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="x-dzenbnf"/><path class="z9r-ch8ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:onekey" {...props}></Icon>
<style>
:global(.x-dzenbnf) {
  cx: 24px;
  cy: 33.557px;
  r: 8.943px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z9r-ch8ck) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 20.09V5.5h-5.218");
}

</style>
