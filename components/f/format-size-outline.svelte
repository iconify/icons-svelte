<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptxucpbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-size-outline" {...props}></Icon>
<style>
:global(.ptxucpbsa) {
  fill: currentColor;
  d: path("M14 20V7H9V4h13v3h-5v13zm-9 0v-8H2V9h9v3H8v8z");
}

</style>
