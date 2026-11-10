<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r-8a0wb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:flexwork" {...props}></Icon>
<style>
:global(.r-8a0wb0b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.706 42.079V17.475L24 5.921l16.294 11.555V42.08zm16.294 0v-10.8");
}

</style>
