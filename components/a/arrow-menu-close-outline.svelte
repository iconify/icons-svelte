<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu6jrdbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-menu-close-outline" {...props}></Icon>
<style>
:global(.fu6jrdbix) {
  fill: currentColor;
  d: path("M11 17V7l-5 5zm2 4h2V3h-2z");
}

</style>
