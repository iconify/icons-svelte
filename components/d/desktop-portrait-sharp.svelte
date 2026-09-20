<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh1jzxbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:desktop-portrait-sharp" {...props}></Icon>
<style>
:global(.eh1jzxbqh) {
  fill: currentColor;
  d: path("M11.154 17.616h4.462V9.154h-4.462zM8.384 15h.885V7.27h3.5v-.886H8.385zM19 21H5V3h14z");
}

</style>
