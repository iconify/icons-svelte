<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w0r4ifbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ostgotatrafiken" {...props}></Icon>
<style>
:global(.w0r4ifbie) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.8 13.847a13.252 13.252 0 1 1-8.518-3.1m0 0H43.5m-28.267 0H4.5");
}

</style>
