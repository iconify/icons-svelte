<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxcw7ob4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:file-copy-sharp" {...props}></Icon>
<style>
:global(.kxcw7ob4v) {
  fill: currentColor;
  d: path("M7 18V2h8.5L20 6.5V18zm8-11h4l-4-4zM3 22V8h1v13h10v1z");
}

</style>
