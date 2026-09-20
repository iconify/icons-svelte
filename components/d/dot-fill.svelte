<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="w19pu26ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:dot-fill" {...props}></Icon>
<style>
:global(.w19pu26ee) {
  fill: currentColor;
  d: path("M128 80a48 48 0 1 0 48 48a48 48 0 0 0-48-48m0 60a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
