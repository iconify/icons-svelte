<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sl63rdyzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:games-tracker" {...props}></Icon>
<style>
:global(.sl63rdyzt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h16v26.36h-16zm0 37h16V31.86m21-10.72V42.5h-16v-37m16 10.64h-16");
}

</style>
