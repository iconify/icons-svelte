<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a9e1jkb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:amboss" {...props}></Icon>
<style>
:global(.a9e1jkb3x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 6L6.394 36.494h35.212l-14.6-25.288L9.227 42h29.546L27.229 22.004");
}

</style>
