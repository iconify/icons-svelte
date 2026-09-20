<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jut3zrwiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:push-pin-simple-light" {...props}></Icon>
<style>
:global(.jut3zrwiw) {
  fill: currentColor;
  d: path("M216 170h-11L183.15 46H192a6 6 0 0 0 0-12H64a6 6 0 0 0 0 12h8.85L51 170H40a6 6 0 0 0 0 12h82v58a6 6 0 0 0 12 0v-58h82a6 6 0 0 0 0-12M85 46h86l21.88 124H63.15Z");
}

</style>
