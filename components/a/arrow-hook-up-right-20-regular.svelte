<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v8bahrb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-hook-up-right-20-regular" {...props}></Icon>
<style>
:global(.v8bahrb5r) {
  fill: currentColor;
  d: path("M4 11a5 5 0 0 0 5 5h4.5a.5.5 0 0 0 0-1H9a4 4 0 0 1 0-8h5.293l-2.7 2.7a.5.5 0 1 0 .708.706l3.539-3.539a.5.5 0 0 0 .125-.497a.5.5 0 0 0-.135-.247L12.297 2.59a.5.5 0 1 0-.707.707L14.293 6H9a5 5 0 0 0-5 5");
}

</style>
