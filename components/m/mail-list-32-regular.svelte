<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="en0yuikex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:mail-list-32-regular" {...props}></Icon>
<style>
:global(.en0yuikex) {
  fill: currentColor;
  d: path("M15.506 5A2.5 2.5 0 0 0 14.5 7h-8A2.5 2.5 0 0 0 4 9.5v.902l12 6.462l6.247-3.364h4.219l-9.992 5.38a1 1 0 0 1-.949 0L4 12.675V22.5A2.5 2.5 0 0 0 6.5 25h19a2.5 2.5 0 0 0 2.5-2.5v-9h2v9a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 22.5v-13A4.5 4.5 0 0 1 6.5 5zM30 10a1 1 0 1 1 0 2H17a1 1 0 1 1 0-2zm0-4a1 1 0 1 1 0 2H17a1 1 0 1 1 0-2zm0-4a1 1 0 1 1 0 2H17a1 1 0 1 1 0-2z");
}

</style>
