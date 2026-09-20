<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o32ra1bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-menu-open-outline" {...props}></Icon>
<style>
:global(.o32ra1bws) {
  fill: currentColor;
  d: path("M9 21V3h2v18zm4-4V7l5 5z");
}

</style>
