<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qappowbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:number-five-thin" {...props}></Icon>
<style>
:global(.qappowbnf) {
  fill: currentColor;
  d: path("M172 160a52 52 0 0 1-86.67 38.76a4 4 0 1 1 5.34-6a44 44 0 1 0 .84-66.33a4 4 0 0 1-6.51-3.79l15.09-75.42A4 4 0 0 1 104 44h64a4 4 0 0 1 0 8h-60.72l-12.51 62.53A52 52 0 0 1 172 160");
}

</style>
