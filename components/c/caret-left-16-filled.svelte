<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gv6nzr8kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-left-16-filled" {...props}></Icon>
<style>
:global(.gv6nzr8kl) {
  fill: currentColor;
  d: path("M9.428 11.84c.663.458 1.571-.013 1.571-.816V4.975c0-.803-.908-1.274-1.571-.816L5.644 6.776a1.486 1.486 0 0 0 0 2.447z");
}

</style>
