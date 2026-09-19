<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dl6s87rrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:revolt-kr" {...props}></Icon>
<style>
:global(.dl6s87rrz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24H12.735L26.287 4.5h11.266zm-2.287 19.5H10.447L24 24h11.265z");
}

</style>
