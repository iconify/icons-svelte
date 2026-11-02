<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_2r053ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mouse-fill" {...props}></Icon>
<style>
:global(.k_2r053ct) {
  fill: currentColor;
  d: path("M5 9a7 7 0 1 1 14 0v6a7 7 0 1 1-14 0Zm8 1V7a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0");
}

</style>
