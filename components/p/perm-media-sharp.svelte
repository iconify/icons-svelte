<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybigkacrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:perm-media-sharp" {...props}></Icon>
<style>
:global(.ybigkacrk) {
  fill: currentColor;
  d: path("M2 19.77V7.076h1v11.692h16v1zm3-3V3h6.577l2 2H22v11.77zM9.461 13h8.693l-2.758-3.654l-2.454 3.077l-1.588-1.884z");
}

</style>
