<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp8v_ebqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rectangle-vertical-fill-round" {...props}></Icon>
<style>
:global(.mp8v_ebqz) {
  fill: currentColor;
  d: path("M11 2h2a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5h-2a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5");
}

</style>
