<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb7y69bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-minimize" {...props}></Icon>
<style>
:global(.vb7y69bfo) {
  fill: currentColor;
  d: path("M6 19h12v2H6z");
}

</style>
