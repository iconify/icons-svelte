<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y5_5qyywr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:boat-progear" {...props}></Icon>
<style>
:global(.y5_5qyywr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.964 43H13.162l-4.466-8.806h30.608zM24 5l-9.371 26.644l17.255-5.664z");
}

</style>
