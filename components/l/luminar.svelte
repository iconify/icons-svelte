<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ztdzbidjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:luminar" {...props}></Icon>
<style>
:global(.ztdzbidjb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24h43M24 2.5v43M8.797 8.797l30.406 30.406m0-30.406L8.797 39.203");
}

</style>
