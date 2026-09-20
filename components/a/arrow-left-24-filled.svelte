<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxr82u8on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-left-24-filled" {...props}></Icon>
<style>
:global(.uxr82u8on) {
  fill: currentColor;
  d: path("M10.295 19.715a1 1 0 0 0 1.404-1.424l-5.37-5.292h13.67a1 1 0 0 0 0-2H6.336L11.7 5.714a1 1 0 0 0-1.404-1.424L3.37 11.112a1.25 1.25 0 0 0 0 1.78z");
}

</style>
