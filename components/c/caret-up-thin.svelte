<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="hpzv9hb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:caret-up-thin" {...props}></Icon>
<style>
:global(.hpzv9hb-m) {
  fill: currentColor;
  d: path("M210.83 162.83a4 4 0 0 1-5.66 0L128 85.66l-77.17 77.17a4 4 0 0 1-5.66-5.66l80-80a4 4 0 0 1 5.66 0l80 80a4 4 0 0 1 0 5.66");
}

</style>
