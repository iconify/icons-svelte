<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="crfjfccrm"/><path class="a4n280z7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lydia" {...props}></Icon>
<style>
:global(.a4n280z7g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.41 33.39L24 11.84l-9.41 21.55");
}

:global(.crfjfccrm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.5 21.5 0 1 1 24 2.5A21.51 21.51 0 0 1 45.5 24");
}

</style>
