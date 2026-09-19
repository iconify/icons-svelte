<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afos8yb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-bar-chart" {...props}></Icon>
<style>
:global(.afos8yb_y) {
  fill: currentColor;
  d: path("M4 9h4v11H4zm12 4h4v7h-4zm-6-9h4v16h-4z");
}

</style>
