<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnay0bb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-commit-fill-round" {...props}></Icon>
<style>
:global(.bnay0bb6i) {
  fill: currentColor;
  d: path("M9.171 13H3a1 1 0 0 1 0-2h6.171a3 3 0 0 1 5.658 0H21a1 1 0 0 1 0 2h-6.171a3 3 0 0 1-5.658 0");
}

</style>
