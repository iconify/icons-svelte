<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="j9yjp7bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:play-button" {...props}></Icon>
<style>
:global(.j9yjp7bte) {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M22 15.5v97L106 64z");
}

</style>
