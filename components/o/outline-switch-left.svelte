<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td2kkx1ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-switch-left" {...props}></Icon>
<style>
:global(.td2kkx1ph) {
  fill: currentColor;
  d: path("M8.5 8.62v6.76L5.12 12zM10 5l-7 7l7 7zm4 0v14l7-7z");
}

</style>
