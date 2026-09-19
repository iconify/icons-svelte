<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmizeqb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-fast-rewind" {...props}></Icon>
<style>
:global(.jmizeqb3b) {
  fill: currentColor;
  d: path("M18 9.86v4.28L14.97 12zm-9 0v4.28L5.97 12zM20 6l-8.5 6l8.5 6zm-9 0l-8.5 6l8.5 6z");
}

</style>
