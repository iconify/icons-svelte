<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boea9c97w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bottom-navigation-outline-sharp" {...props}></Icon>
<style>
:global(.boea9c97w) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-4.615h14V5H5zm0 1V19h14v-2.616zm0 0V19z");
}

</style>
