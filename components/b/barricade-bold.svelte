<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mkzzhmrwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:barricade-bold" {...props}></Icon>
<style>
:global(.mkzzhmrwh) {
  fill: currentColor;
  d: path("M224 60H32a20 20 0 0 0-20 20v72a20 20 0 0 0 20 20h20v28a12 12 0 0 0 24 0v-28h104v28a12 12 0 0 0 24 0v-28h20a20 20 0 0 0 20-20V80a20 20 0 0 0-20-20m-4 59l-35-35h35Zm-43 29l-64-64h38l64 64Zm-72 0L41 84h38l64 64Zm-69-35l35 35H36Z");
}

</style>
