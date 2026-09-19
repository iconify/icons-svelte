<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ghm8osbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:flutter" {...props}></Icon>
<style>
:global(.ghm8osbtm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.592 38.574l16.859-16.045H27.768L16.75 33.014L27.768 43.5h11.683L28.433 33.014M7.636 24.34l5.94 5.654L40.364 4.5H28.681z");
}

</style>
