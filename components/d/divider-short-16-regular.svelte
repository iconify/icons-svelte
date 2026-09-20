<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yhihwcb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:divider-short-16-regular" {...props}></Icon>
<style>
:global(.yhihwcb_f) {
  fill: currentColor;
  d: path("M7.5 3a.5.5 0 0 1 .5.5v9a.5.5 0 0 1-1 0v-9a.5.5 0 0 1 .5-.5");
}

</style>
