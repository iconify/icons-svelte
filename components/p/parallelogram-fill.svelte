<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="o138w_p7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:parallelogram-fill" {...props}></Icon>
<style>
:global(.o138w_p7b) {
  fill: currentColor;
  d: path("m246.58 62.57l-64.8 144a16 16 0 0 1-14.59 9.43H24a16 16 0 0 1-14.58-22.57l64.8-144A16 16 0 0 1 88.81 40H232a16 16 0 0 1 14.59 22.57Z");
}

</style>
