<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i-o6r7aol"/><circle class="c6nojbb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lidentit-numrique" {...props}></Icon>
<style>
:global(.c6nojbb-z) {
  cx: 24px;
  cy: 7.581px;
  r: 3.081px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i-o6r7aol) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.206 43.5V23.828a6.725 6.725 0 0 0-6.725-6.725H24V34.45M9.794 17.103v19.672A6.725 6.725 0 0 0 16.52 43.5H24");
}

</style>
