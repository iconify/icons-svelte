<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c7uky3qvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:exclamation-mark-bold" {...props}></Icon>
<style>
:global(.c7uky3qvc) {
  fill: currentColor;
  d: path("M148 200a20 20 0 1 1-20-20a20 20 0 0 1 20 20m-20-40a12 12 0 0 0 12-12V48a12 12 0 0 0-24 0v100a12 12 0 0 0 12 12");
}

</style>
