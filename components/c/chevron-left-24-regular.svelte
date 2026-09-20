<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t50e0ynzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-left-24-regular" {...props}></Icon>
<style>
:global(.t50e0ynzg) {
  fill: currentColor;
  d: path("M15.53 4.22a.75.75 0 0 1 0 1.06L8.81 12l6.72 6.72a.75.75 0 1 1-1.06 1.06l-7.25-7.25a.75.75 0 0 1 0-1.06l7.25-7.25a.75.75 0 0 1 1.06 0");
}

</style>
