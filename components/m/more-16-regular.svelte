<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v78tlgbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-16-regular" {...props}></Icon>
<style>
:global(.v78tlgbya) {
  d: path("M4 7a1 1 0 1 1 0 2a1 1 0 0 1 0-2zm4 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2zm4 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2z");
  fill: currentColor;
  fill-rule: nonzero;
}

</style>
