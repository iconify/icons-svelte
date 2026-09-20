<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7o_l_b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-menu-close-sharp" {...props}></Icon>
<style>
:global(.z7o_l_b5v) {
  fill: currentColor;
  d: path("M10.616 15.635v-7.25L7.135 12zM13 20h1V4h-1z");
}

</style>
