<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x0b81owrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:dot" {...props}></Icon>
<style>
:global(.x0b81owrb) {
  fill: currentColor;
  d: path("M140 128a12 12 0 1 1-12-12a12 12 0 0 1 12 12");
}

</style>
