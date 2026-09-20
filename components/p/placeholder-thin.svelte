<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="g5a1bc04e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:placeholder-thin" {...props}></Icon>
<style>
:global(.g5a1bc04e) {
  fill: currentColor;
  d: path("M208 36H48a12 12 0 0 0-12 12v160a12 12 0 0 0 12 12h160a12 12 0 0 0 12-12V48a12 12 0 0 0-12-12m4 12v158.34L49.66 44H208a4 4 0 0 1 4 4M44 208V49.66L206.34 212H48a4 4 0 0 1-4-4");
}

</style>
