<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1flj2jew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:highlight-accent-24-filled" {...props}></Icon>
<style>
:global(.i1flj2jew) {
  fill: currentColor;
  d: path("M20.003 4L20 7.75l-.007.102a.754.754 0 0 1-.71.648H4.737l-.089-.006A.75.75 0 0 1 4 7.751V4zm-4.496 9.5H8.5V21l6.576-3.106a.75.75 0 0 0 .424-.572l.008-.107z");
}

</style>
