<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmjgekb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-24-regular" {...props}></Icon>
<style>
:global(.fmjgekb1o) {
  fill: currentColor;
  d: path("M12 3.5a8.5 8.5 0 1 0 0 17a8.5 8.5 0 0 0 0-17M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
