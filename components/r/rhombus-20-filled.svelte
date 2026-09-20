<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cnvggubzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:rhombus-20-filled" {...props}></Icon>
<style>
:global(.cnvggubzb) {
  fill: currentColor;
  d: path("M4.89 4.296A2 2 0 0 1 6.76 3h10.237a2 2 0 0 1 1.872 2.704l-3.76 10A2 2 0 0 1 13.238 17H3.001a2 2 0 0 1-1.872-2.704z");
}

</style>
