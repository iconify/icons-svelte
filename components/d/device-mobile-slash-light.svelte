<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="izdu86xbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:device-mobile-slash-light" {...props}></Icon>
<style>
:global(.izdu86xbc) {
  fill: currentColor;
  d: path("m212.44 212l-160-176a6 6 0 0 0-8.88 8L58 59.92V216a22 22 0 0 0 22 22h96a22 22 0 0 0 22-22v-2.08l5.56 6.12a6 6 0 0 0 8.88-8.08ZM186 216a10 10 0 0 1-10 10H80a10 10 0 0 1-10-10V73.12l116 127.6ZM70.7 24a6 6 0 0 1 6-6H176a22 22 0 0 1 22 22v110.83a6 6 0 1 1-12 0V40a10 10 0 0 0-10-10H76.7a6 6 0 0 1-6-6");
}

</style>
