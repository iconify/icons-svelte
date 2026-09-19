<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="nvtqfobhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:red-triangle-pointed-down" {...props}></Icon>
<style>
:global(.nvtqfobhl) {
  fill: currentColor;
  d: path("M32 62L62 2H2z");
}

</style>
