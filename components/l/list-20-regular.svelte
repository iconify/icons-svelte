<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="avnpigekk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:list-20-regular" {...props}></Icon>
<style>
:global(.avnpigekk) {
  fill: currentColor;
  d: path("M2 4.5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5m0 10a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1h-10a.5.5 0 0 1-.5-.5M2.5 9a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1z");
}

</style>
