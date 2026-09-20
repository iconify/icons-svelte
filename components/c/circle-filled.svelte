<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n-0e6zbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:circle-filled" {...props}></Icon>
<style>
:global(.n-0e6zbvg) {
  fill: currentColor;
  d: path("M16.5 10a6.5 6.5 0 1 1-13 0a6.5 6.5 0 0 1 13 0");
}

</style>
