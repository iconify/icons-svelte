<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6ekypzqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-flash-on" {...props}></Icon>
<style>
:global(.k6ekypzqk) {
  fill: currentColor;
  d: path("M7 2v11h3v9l7-12h-4l4-8z");
}

</style>
