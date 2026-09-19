<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="odm8f5bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:aria2app" {...props}></Icon>
<style>
:global(.odm8f5bwi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.116 26.932h17.768m4.616-8.329L23.999 43.5L10.5 18.603M24 21.427V4.5");
}

</style>
