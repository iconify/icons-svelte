<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="eie6ozb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:device-mobile-slash-thin" {...props}></Icon>
<style>
:global(.eie6ozb8w) {
  fill: currentColor;
  d: path("m211 213.31l-160-176a4 4 0 0 0-6 5.38l15 16.46V216a20 20 0 0 0 20 20h96a20 20 0 0 0 20-20v-7.25l9 9.94a4 4 0 1 0 5.92-5.38ZM188 216a12 12 0 0 1-12 12H80a12 12 0 0 1-12-12V68l120 132ZM72.7 24a4 4 0 0 1 4-4H176a20 20 0 0 1 20 20v110.83a4 4 0 1 1-8 0V40a12 12 0 0 0-12-12H76.7a4 4 0 0 1-4-4");
}

</style>
