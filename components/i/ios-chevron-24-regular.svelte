<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rry0mjnrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:ios-chevron-24-regular" {...props}></Icon>
<style>
:global(.rry0mjnrj) {
  d: path("M13.97 4.72a.75.75 0 0 0 0 1.06L20.19 12l-6.22 6.22a.75.75 0 1 0 1.06 1.06l6.75-6.75a.75.75 0 0 0 0-1.06l-6.75-6.75a.75.75 0 0 0-1.06 0z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>
