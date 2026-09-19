<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wrz6btrdz"/><path class="we91-1b2s"/><path class="r81qvjtya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:naver-prism" {...props}></Icon>
<style>
:global(.r81qvjtya) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 6.629l19 34.743H5z");
}

:global(.we91-1b2s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 12.415l14.299 26.242H9.7z");
}

:global(.wrz6btrdz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 18.213l9.652 17.545H14.348z");
}

</style>
