<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="w3u1qjuon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:exclamation-mark" {...props}></Icon>
<style>
:global(.w3u1qjuon) {
  fill: currentColor;
  d: path("M144 200a16 16 0 1 1-16-16a16 16 0 0 1 16 16m-16-40a8 8 0 0 0 8-8V48a8 8 0 0 0-16 0v104a8 8 0 0 0 8 8");
}

</style>
