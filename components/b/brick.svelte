<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymmezihid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:brick" {...props}></Icon>
<style>
:global(.ymmezihid) {
  fill: currentColor;
  d: path("M3 19V8.712h2.827V5h4.789v3.712h2.769V5h4.788v3.712H21V19z");
}

</style>
