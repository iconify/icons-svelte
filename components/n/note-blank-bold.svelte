<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="kbcmm5vzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:note-blank-bold" {...props}></Icon>
<style>
:global(.kbcmm5vzc) {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h108.69a19.86 19.86 0 0 0 14.14-5.86l51.31-51.31a19.86 19.86 0 0 0 5.86-14.14V48a20 20 0 0 0-20-20M52 52h152v92h-48a12 12 0 0 0-12 12v48H52Zm116 139v-23h23Z");
}

</style>
