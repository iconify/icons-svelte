<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="o0m1bxb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:red-triangle-pointed-up" {...props}></Icon>
<style>
:global(.o0m1bxb5n) {
  fill: currentColor;
  d: path("M32 2L2 62h60z");
}

</style>
