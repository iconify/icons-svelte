<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1h0hhzfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:mtd" {...props}></Icon>
<style>
:global(.s1h0hhzfp) {
  fill: var(--svg-color--ff1826, #ff1826);
  d: path("M3 16.5h13.5V3H21v18H3zM3 3h4.5v7.072H3zm6.429 0h4.5v7.072h-4.5z");
}

</style>
