<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itwjg14iq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pause-sharp" {...props}></Icon>
<style>
:global(.itwjg14iq) {
  fill: currentColor;
  d: path("M14 19V5h4v14zm-8 0V5h4v14z");
}

</style>
