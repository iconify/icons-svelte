<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jyz35hbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:clock-12-filled" {...props}></Icon>
<style>
:global(.jyz35hbpy) {
  fill: currentColor;
  d: path("M6 1a5 5 0 1 1 0 10A5 5 0 0 1 6 1m-.5 2.5A.5.5 0 0 0 5 4v2.5a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1H6V4a.5.5 0 0 0-.5-.5");
}

</style>
