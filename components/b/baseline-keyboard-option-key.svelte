<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhh-k1b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-keyboard-option-key" {...props}></Icon>
<style>
:global(.zhh-k1b_k) {
  fill: currentColor;
  d: path("M15 5h6v2h-6zM9 5H3v2h4.85l6.92 12H21v-2h-5.07z");
}

</style>
