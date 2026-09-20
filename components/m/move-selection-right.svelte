<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-e75ynwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:move-selection-right" {...props}></Icon>
<style>
:global(.l-e75ynwg) {
  fill: currentColor;
  d: path("M10.923 17.039V6.961H21v10.077zm-3.961 0v-1.231h1.23v1.23zm0-8.847v-1.23h1.23v1.23zM3 17.038v-1.23h1.23v1.23zm0-4.423v-1.23h1.23v1.23zm0-4.423v-1.23h1.23v1.23z");
}

</style>
