<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo3ei4bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-fork-fill-round" {...props}></Icon>
<style>
:global(.eo3ei4bil) {
  fill: currentColor;
  d: path("M6.104 8.79A3.01 3.01 0 0 0 9 11h6a3.01 3.01 0 0 0 2.896-2.21a3 3 0 1 1 2.032.064A5.01 5.01 0 0 1 15 13h-2v2.171a3 3 0 1 1-2 0V13H9a5.006 5.006 0 0 1-4.928-4.146a3.001 3.001 0 1 1 2.032-.064");
}

</style>
