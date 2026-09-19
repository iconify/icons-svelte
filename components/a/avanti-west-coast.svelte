<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rt3c25ite"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:avanti-west-coast" {...props}></Icon>
<style>
:global(.rt3c25ite) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.749 30.294L39.499 43.5L24 4.5zM14.903 43.5L11.7 35.512L8.5 43.5m1.067-2.663h4.268");
}

</style>
