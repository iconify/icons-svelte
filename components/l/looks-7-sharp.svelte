<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmukt-ypk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:looks-7-sharp" {...props}></Icon>
<style>
:global(.vmukt-ypk) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5zm0 0V5h14v14zm6.462-2.5H12.5l2-7.936V7.5h-5v1h3.962z");
}

</style>
