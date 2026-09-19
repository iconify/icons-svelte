<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kcsvgablb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:business-suite" {...props}></Icon>
<style>
:global(.kcsvgablb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.33 34.669A21.51 21.51 0 0 1 8.796 8.797L24 24L8.797 39.203A21.497 21.497 0 1 0 13.33 5.33");
}

</style>
