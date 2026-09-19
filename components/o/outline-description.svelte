<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks64glbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-description" {...props}></Icon>
<style>
:global(.ks64glbdq) {
  fill: currentColor;
  d: path("M8 16h8v2H8zm0-4h8v2H8zm6-10H6c-1.1 0-2 .9-2 2v16c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8zm4 18H6V4h7v5h5z");
}

</style>
