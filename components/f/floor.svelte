<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1re1x9eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:floor" {...props}></Icon>
<style>
:global(.s1re1x9eu) {
  fill: var(--svg-color--00f3d5, #00f3d5);
  d: path("M3 10.941h18v2.118H3z");
}

</style>
