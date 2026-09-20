<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cbi3x0bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:line-vertical-thin" {...props}></Icon>
<style>
:global(.cbi3x0bda) {
  fill: currentColor;
  d: path("M132 24v208a4 4 0 0 1-8 0V24a4 4 0 0 1 8 0");
}

</style>
