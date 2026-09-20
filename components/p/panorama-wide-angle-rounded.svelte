<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw8x0z94m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:panorama-wide-angle-rounded" {...props}></Icon>
<style>
:global(.sw8x0z94m) {
  fill: currentColor;
  d: path("M7.463 19.788Q5.2 19.575 3 19q-.525-1.725-.763-3.463T2 12t.238-3.537T3 5q1.975-.5 4.2-.75T12 4t4.8.25T21 5q.525 1.725.763 3.463T22 12t-.25 3.538T21 19q-2.2.575-4.462.788T12 20t-4.538-.213");
}

</style>
