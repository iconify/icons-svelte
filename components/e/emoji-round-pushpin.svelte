<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r4n6-z5bz"/><path class="b0pr8ac9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emoji-round-pushpin" {...props}></Icon>
<style>
:global(.b0pr8ac9d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.003 13.493c0 4.414 3.58 7.993 7.997 7.993s7.997-3.579 7.997-7.993S28.417 5.5 24 5.5s-7.997 3.579-7.997 7.993");
}

:global(.r4n6-z5bz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.726 21.298v15.445l-1.75 5.757l-2.042-5.757V21.215");
}

</style>
