<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uczfh3-ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ameritrade" {...props}></Icon>
<style>
:global(.uczfh3-ew) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 15.13l-1.733 8.534M4.5 32.87l11.768-11.768l10.63 10.63l15.016-15.016L43.5 15.13l-8.44 1.6");
}

</style>
