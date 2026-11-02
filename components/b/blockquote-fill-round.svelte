<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_vw0tbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:blockquote-fill-round" {...props}></Icon>
<style>
:global(.v_vw0tbqh) {
  fill: currentColor;
  d: path("M5 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0m3-1h12a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m0 4h12a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m0 4h12a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m0 4h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

</style>
