<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m0f6ygben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:manoramamax" {...props}></Icon>
<style>
:global(.m0f6ygben) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 24L5.5 40.67V7.33h37v33.34L33.25 24L24 40.67L5.5 7.33");
}

</style>
