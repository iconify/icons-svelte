<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz2kiccjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:lists-outline-sharp" {...props}></Icon>
<style>
:global(.uz2kiccjn) {
  fill: currentColor;
  d: path("M2 20v-4h4v4zm6 0v-4h14v4zm-6-6v-4h4v4zm6 0v-4h14v4zM2 8V4h4v4zm6 0V4h14v4z");
}

</style>
