<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1-1yjr8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:last-page" {...props}></Icon>
<style>
:global(.m1-1yjr8e) {
  fill: currentColor;
  d: path("M5.59 7.41L10.18 12l-4.59 4.59L7 18l6-6l-6-6zM16 6h2v12h-2z");
}

</style>
