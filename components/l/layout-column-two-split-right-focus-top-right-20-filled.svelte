<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e_vzicbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-column-two-split-right-focus-top-right-20-filled" {...props}></Icon>
<style>
:global(.e_vzicbvi) {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm3-2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h3.5V4zm8 12a2 2 0 0 0 2-2v-4h-5.5v6z");
}

</style>
