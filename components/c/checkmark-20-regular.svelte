<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rs_w9tb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:checkmark-20-regular" {...props}></Icon>
<style>
:global(.rs_w9tb8y) {
  fill: currentColor;
  d: path("M3.374 10.168a.5.5 0 0 0-.748.664l4 4.5a.5.5 0 0 0 .728.022l10.5-10.5a.5.5 0 0 0-.707-.708L7.02 14.271z");
}

</style>
