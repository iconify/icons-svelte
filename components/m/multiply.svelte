<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="segp53btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:multiply" {...props}></Icon>
<style>
:global(.segp53btz) {
  fill: currentColor;
  d: path("M62 10.571L53.428 2L32 23.429L10.571 2L2 10.571L23.428 32L2 53.429L10.571 62L32 40.571L53.428 62L62 53.429L40.57 32z");
}

</style>
