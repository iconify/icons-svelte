<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7vsbhs2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:divider-short-24-filled" {...props}></Icon>
<style>
:global(.p7vsbhs2e) {
  fill: currentColor;
  d: path("M11 5v14a1 1 0 1 0 2 0V5a1 1 0 1 0-2 0");
}

</style>
