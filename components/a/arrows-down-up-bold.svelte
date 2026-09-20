<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ygk-39sha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrows-down-up-bold" {...props}></Icon>
<style>
:global(.ygk-39sha) {
  fill: currentColor;
  d: path("M120.49 167.51a12 12 0 0 1 0 17l-32 32a12 12 0 0 1-17 0l-32-32a12 12 0 1 1 17-17L68 179V48a12 12 0 0 1 24 0v131l11.51-11.52a12 12 0 0 1 16.98.03m96-96l-32-32a12 12 0 0 0-17 0l-32 32a12 12 0 0 0 17 17L164 77v131a12 12 0 0 0 24 0V77l11.51 11.52a12 12 0 0 0 17-17Z");
}

</style>
