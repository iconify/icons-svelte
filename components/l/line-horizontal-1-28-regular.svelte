<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="iecfkvboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-1-28-regular" {...props}></Icon>
<style>
:global(.iecfkvboc) {
  fill: currentColor;
  d: path("M2 13.75a.75.75 0 0 1 .75-.75h22.5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1-.75-.75");
}

</style>
