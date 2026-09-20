<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jc7b79alk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-down-left-16-filled" {...props}></Icon>
<style>
:global(.jc7b79alk) {
  fill: currentColor;
  d: path("M12 4.957c0-.89-1.077-1.337-1.707-.707L4.25 10.293c-.63.63-.184 1.707.707 1.707H10.5a1.5 1.5 0 0 0 1.5-1.5z");
}

</style>
