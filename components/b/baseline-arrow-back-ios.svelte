<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr3glibor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-arrow-back-ios" {...props}></Icon>
<style>
:global(.qr3glibor) {
  fill: currentColor;
  d: path("M11.67 3.87L9.9 2.1L0 12l9.9 9.9l1.77-1.77L3.54 12z");
}

</style>
