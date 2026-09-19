<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nlsmhs68s"/><path class="i0h883bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:iss-vanguard" {...props}></Icon>
<style>
:global(.i0h883bjf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.772 17.44h5.404l5.805 9.642l6.098-9.86h5.112l-11.21 19.28zM5.511 9.7l-.51-1.168h10.953M42.489 9.7L43 8.533H32.046m-13.973-.001h11.684M7.336 13.06H40.42");
}

:global(.nlsmhs68s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.282 16.706L23.988 41.468L9.68 17.222");
}

</style>
