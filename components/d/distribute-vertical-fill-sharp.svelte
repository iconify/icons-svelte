<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi3o2g18e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:distribute-vertical-fill-sharp" {...props}></Icon>
<style>
:global(.hi3o2g18e) {
  fill: currentColor;
  d: path("M21 3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2ZM5 9a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1Zm16 10a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
