<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykwu1pbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pentagon-sharp" {...props}></Icon>
<style>
:global(.ykwu1pbea) {
  fill: currentColor;
  d: path("M6 21L2 9l10-7l10 7l-4 12z");
}

</style>
