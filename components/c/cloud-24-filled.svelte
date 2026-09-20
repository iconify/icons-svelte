<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik0xe9bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cloud-24-filled" {...props}></Icon>
<style>
:global(.ik0xe9bhi) {
  fill: currentColor;
  d: path("M6.08 9.02a6.001 6.001 0 0 1 11.84 0A4.5 4.5 0 0 1 17.5 18h-11a4.5 4.5 0 0 1-.42-8.98");
}

</style>
