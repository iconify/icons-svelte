<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0z7yppkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-spoke" {...props}></Icon>
<style>
:global(.f0z7yppkn) {
  fill: currentColor;
  d: path("M16 7c0 2.21-1.79 4-4 4S8 9.21 8 7s1.79-4 4-4s4 1.79 4 4m-9 6c-2.21 0-4 1.79-4 4s1.79 4 4 4s4-1.79 4-4s-1.79-4-4-4m10 0c-2.21 0-4 1.79-4 4s1.79 4 4 4s4-1.79 4-4s-1.79-4-4-4");
}

</style>
