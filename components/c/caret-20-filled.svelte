<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tj36kntje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-20-filled" {...props}></Icon>
<style>
:global(.tj36kntje) {
  fill: currentColor;
  d: path("M15 5.957c0-.89-1.077-1.337-1.707-.707L5.25 13.293c-.63.63-.184 1.707.707 1.707H13.5a1.5 1.5 0 0 0 1.5-1.5z");
}

</style>
