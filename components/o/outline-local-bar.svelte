<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1_khlb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-local-bar" {...props}></Icon>
<style>
:global(.g1_khlb9p) {
  fill: currentColor;
  d: path("M14.77 9L12 12.11L9.23 9zM21 3H3v2l8 9v5H6v2h12v-2h-5v-5l8-9zM7.43 7L5.66 5h12.69l-1.78 2z");
}

</style>
