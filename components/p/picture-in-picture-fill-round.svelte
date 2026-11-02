<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b46jhob4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:picture-in-picture-fill-round" {...props}></Icon>
<style>
:global(.b46jhob4i) {
  fill: currentColor;
  d: path("M7 3h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5m6 14h2a3 3 0 1 0 0-6h-2a3 3 0 1 0 0 6");
}

</style>
