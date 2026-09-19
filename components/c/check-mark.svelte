<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ikmse57kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:check-mark" {...props}></Icon>
<style>
:global(.ikmse57kr) {
  fill: currentColor;
  d: path("M56 2L18.8 42.909L8 34.729H2L18.8 62L62 2z");
}

</style>
