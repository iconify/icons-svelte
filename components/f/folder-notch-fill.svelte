<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cxkv-un3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:folder-notch-fill" {...props}></Icon>
<style>
:global(.cxkv-un3e) {
  fill: currentColor;
  d: path("M216 72h-85.34l-27.74-20.8a16 16 0 0 0-9.58-3.2H40a16 16 0 0 0-16 16v136a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V88a16 16 0 0 0-16-16M40 64h53.34l21.33 16l-21.34 16H40Z");
}

</style>
