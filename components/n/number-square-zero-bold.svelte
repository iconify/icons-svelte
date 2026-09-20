<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ntdif7r6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:number-square-zero-bold" {...props}></Icon>
<style>
:global(.ntdif7r6u) {
  fill: currentColor;
  d: path("M128 188c28.26 0 48-24.67 48-60s-19.74-60-48-60s-48 24.67-48 60s19.74 60 48 60m0-96c23.33 0 24 32.32 24 36s-.67 36-24 36s-24-32.32-24-36s.67-36 24-36m80-64H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H52V52h152Z");
}

</style>
