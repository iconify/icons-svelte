<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ihvqhub0d"/><path class="e5i4m6b2p"/><path class="n7qolkbmo"/><path class="chonn-b8y"/><path class="k_gt4qwze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:angel-aura-amethyst" {...props}></Icon>
<style>
:global(.chonn-b8y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.552 36.899V19.7l14.894-8.601");
}

:global(.e5i4m6b2p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5V24l18.618-10.752M9.104 32.599V15.4l14.894-8.601");
}

:global(.ihvqhub0d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l18.62 10.75v21.5L24 45.5L5.38 34.75v-21.5z");
}

:global(.k_gt4qwze) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.276 39.049V21.85l14.894-8.601");
}

:global(.n7qolkbmo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.828 34.749V17.55l14.894-8.601");
}

</style>
