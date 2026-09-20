<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="o2qd2hb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:line-vertical" {...props}></Icon>
<style>
:global(.o2qd2hb1p) {
  fill: currentColor;
  d: path("M136 24v208a8 8 0 0 1-16 0V24a8 8 0 0 1 16 0");
}

</style>
