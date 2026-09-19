<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bbwroj02y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:edge-gestures" {...props}></Icon>
<style>
:global(.bbwroj02y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.192 42.387l6.167.057V5.5H7.193m33.616.113l-6.168-.057V42.5h6.168");
}

</style>
