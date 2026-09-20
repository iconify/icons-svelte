<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="niu0fc39t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-flow-diagonal-up-right-20-filled" {...props}></Icon>
<style>
:global(.niu0fc39t) {
  fill: currentColor;
  d: path("M15.854 4.854a.5.5 0 0 0-.708-.708l-7.408 7.409a3 3 0 1 0 .707.707z");
}

</style>
