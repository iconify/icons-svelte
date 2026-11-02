<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoaz3pbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:laptop-fill" {...props}></Icon>
<style>
:global(.zoaz3pbkd) {
  fill: currentColor;
  d: path("M4 15.171V6a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v9.171A3.001 3.001 0 0 1 19 21H5a3 3 0 0 1-1-5.829M5 17a1 1 0 0 0 0 2h14a1 1 0 0 0 0-2Z");
}

</style>
