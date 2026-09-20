<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzy5p-bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:expand-less" {...props}></Icon>
<style>
:global(.uzy5p-bcz) {
  fill: currentColor;
  d: path("m7.4 14.702l-.708-.708L12 8.687l5.308 5.307l-.708.708l-4.6-4.6z");
}

</style>
