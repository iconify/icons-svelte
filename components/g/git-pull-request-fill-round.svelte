<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi92mggmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-pull-request-fill-round" {...props}></Icon>
<style>
:global(.fi92mggmg) {
  fill: currentColor;
  d: path("M15 5a5 5 0 0 1 5 5v5.171a3 3 0 1 1-2 0V10a3 3 0 0 0-3-3h-1.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L13.414 5ZM6 8.829v6.342a3 3 0 1 1-2 0V8.829a3 3 0 1 1 2 0");
}

</style>
