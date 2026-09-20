<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="crb63ug3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:presence-busy-10-filled" {...props}></Icon>
<style>
:global(.crb63ug3l) {
  fill: currentColor;
  d: path("M10 5A5 5 0 1 1 0 5a5 5 0 0 1 10 0");
}

</style>
