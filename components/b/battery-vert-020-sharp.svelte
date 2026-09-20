<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7hn0fh2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-vert-020-sharp" {...props}></Icon>
<style>
:global(.o7hn0fh2x) {
  fill: currentColor;
  d: path("M9 17h6V6H9v11Zm-2 5V4h3V2h4v2h3v18H7Z");
}

</style>
