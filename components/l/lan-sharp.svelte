<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp9u1ybns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:lan-sharp" {...props}></Icon>
<style>
:global(.cp9u1ybns) {
  fill: currentColor;
  d: path("M3 22v-7h3v-4h5V9H8V2h8v7h-3v2h5v4h3v7h-8v-7h3v-2H8v2h3v7z");
}

</style>
