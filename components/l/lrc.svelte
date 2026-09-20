<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pohvsdqhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:lrc" {...props}></Icon>
<style>
:global(.pohvsdqhp) {
  fill: var(--svg-color--1f63ff, #1f63ff);
  d: path("M8.992 5.116v13.767L3 13.993zm.001 13.767l5.654-4.889l-1.644-2.582H21z");
}

</style>
