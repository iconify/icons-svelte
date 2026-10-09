<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvswcrb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:looks-7-outline-sharp" {...props}></Icon>
<style>
:global(.yvswcrb6p) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5zm0 0V5zm6.462-2.5H12.5l2-7.936V7.5h-5v1h3.962z");
}

</style>
