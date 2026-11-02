<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlelzyjma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mobile-button-fill" {...props}></Icon>
<style>
:global(.zlelzyjma) {
  fill: currentColor;
  d: path("M6 5a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3Zm6.01 12H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
