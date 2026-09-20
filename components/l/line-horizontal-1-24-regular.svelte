<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueh43-05j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-1-24-regular" {...props}></Icon>
<style>
:global(.ueh43-05j) {
  fill: currentColor;
  d: path("M2 11.75a.75.75 0 0 1 .75-.75h18.5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1-.75-.75");
}

</style>
