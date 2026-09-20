<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8c_5d7bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:divider-tall-24-regular" {...props}></Icon>
<style>
:global(.t8c_5d7bh) {
  fill: currentColor;
  d: path("M11.25 2.75v18.5a.75.75 0 0 0 1.5 0V2.75a.75.75 0 0 0-1.5 0");
}

</style>
