<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xqa70t7kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:flag-pennant-fill" {...props}></Icon>
<style>
:global(.xqa70t7kg) {
  fill: currentColor;
  d: path("M248 104a8 8 0 0 1-5.37 7.56L64 173.69V216a8 8 0 0 1-16 0V40a8 8 0 0 1 10.63-7.56l184 64A8 8 0 0 1 248 104");
}

</style>
