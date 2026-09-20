<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="reixkd6wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:hov-outline" {...props}></Icon>
<style>
:global(.reixkd6wc) {
  fill: currentColor;
  d: path("m12 21l-5-9.02L12 3l5 8.98zm0-2.034l3.848-6.985L12 5.035L8.152 11.98zM12 12");
}

</style>
