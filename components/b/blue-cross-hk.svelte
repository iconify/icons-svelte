<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c0gbbdc7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:blue-cross-hk" {...props}></Icon>
<style>
:global(.c0gbbdc7z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 13H35V5.5H13V13H5.5v22H13v7.5h22V35h7.5z");
}

</style>
