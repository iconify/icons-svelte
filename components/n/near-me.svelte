<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umy8kdbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:near-me" {...props}></Icon>
<style>
:global(.umy8kdbsc) {
  fill: currentColor;
  d: path("M21 3L3 10.53v.98l6.84 2.65L12.48 21h.98z");
}

</style>
