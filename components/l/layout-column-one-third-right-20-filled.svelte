<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bgj64vggy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-column-one-third-right-20-filled" {...props}></Icon>
<style>
:global(.bgj64vggy) {
  fill: currentColor;
  d: path("M13 17h1a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3h-1zM12 3H6a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h6z");
}

</style>
