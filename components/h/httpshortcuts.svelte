<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ll6d4ewnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:httpshortcuts" {...props}></Icon>
<style>
:global(.ll6d4ewnz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.349 23.878h27.4L12.35 4.5Zm0 0L8.25 43.5l31.498-19.622");
}

</style>
