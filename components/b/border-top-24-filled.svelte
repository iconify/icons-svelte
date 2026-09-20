<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3gcd2k0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:border-top-24-filled" {...props}></Icon>
<style>
:global(.b3gcd2k0k) {
  fill: currentColor;
  d: path("M3 6a1 1 0 0 0 2 0a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1a1 1 0 1 0 2 0a3 3 0 0 0-3-3H6a3 3 0 0 0-3 3m2 5a1 1 0 1 0-2 0v2a1 1 0 1 0 2 0zm14 0a1 1 0 1 1 2 0v2a1 1 0 1 1-2 0zm-5 9a1 1 0 0 1-1 1h-2a1 1 0 1 1 0-2h2a1 1 0 0 1 1 1m-8 1a1 1 0 1 0 0-2a1 1 0 0 1-1-1a1 1 0 1 0-2 0a3 3 0 0 0 3 3m11-1a1 1 0 0 0 1 1a3 3 0 0 0 3-3a1 1 0 1 0-2 0a1 1 0 0 1-1 1a1 1 0 0 0-1 1");
}

</style>
