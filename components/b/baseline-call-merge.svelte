<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lebgayb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-call-merge" {...props}></Icon>
<style>
:global(.lebgayb6s) {
  fill: currentColor;
  d: path("M17 20.41L18.41 19L15 15.59L13.59 17zM7.5 8H11v5.59L5.59 19L7 20.41l6-6V8h3.5L12 3.5z");
}

</style>
