<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sfy76uwxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-line-12-regular" {...props}></Icon>
<style>
:global(.sfy76uwxa) {
  fill: currentColor;
  d: path("M6 1a5 5 0 1 0 0 10A5 5 0 0 0 6 1M2 6a4 4 0 1 1 8 0zm.126 1h7.748a4.002 4.002 0 0 1-7.748 0");
}

</style>
