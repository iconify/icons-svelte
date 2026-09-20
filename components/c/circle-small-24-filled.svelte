<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwuekqkoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-small-24-filled" {...props}></Icon>
<style>
:global(.fwuekqkoy) {
  fill: currentColor;
  d: path("M8 12a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

</style>
