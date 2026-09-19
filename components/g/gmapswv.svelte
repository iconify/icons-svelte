<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ppj6_ib-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gmapswv" {...props}></Icon>
<style>
:global(.ppj6_ib-a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37.363L37.884 43.5l1.287-1.584L24 4.5L8.829 41.916l1.287 1.584z");
}

</style>
