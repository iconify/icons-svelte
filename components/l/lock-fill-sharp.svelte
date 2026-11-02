<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3myfbcrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-fill-sharp" {...props}></Icon>
<style>
:global(.q3myfbcrz) {
  fill: currentColor;
  d: path("M8 9V6a4 4 0 0 1 8 0v3h4a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1Zm6-3a2 2 0 1 0-4 0v3h4Z");
}

</style>
