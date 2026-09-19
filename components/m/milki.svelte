<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="srftabcrw"/><circle class="y47uifm4f"/><circle class="vvvjzbcoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:milki" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.srftabcrw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.958 19.342l1.282-.59c.609-.279 1.216-.572 1.757-.966s1.016-.882 1.382-1.443m15.663 2.999l-1.282-.59c-.609-.279-1.216-.572-1.757-.966s-1.016-.882-1.382-1.443m-9.568 14.614l1.327.331c.812.203 1.639.37 2.476.368s1.665-.158 2.485-.326q.804-.164 1.607-.335");
}

:global(.vvvjzbcoz) {
  cx: 31.831px;
  cy: 23.115px;
  r: 1.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.y47uifm4f) {
  cx: 16.478px;
  cy: 23.115px;
  r: 1.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
