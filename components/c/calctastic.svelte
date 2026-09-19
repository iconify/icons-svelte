<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bugdvbbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calctastic" {...props}></Icon>
<style>
:global(.bugdvbbkr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.409 36.409h27.182V43.5H10.409zm27.182-21.864H27.545V4.5h-7.09v10.045H10.409v7.091h10.046v10.046h7.09V21.636h10.046z");
}

</style>
