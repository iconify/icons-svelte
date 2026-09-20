<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3jdr0bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bottom-panel-close-sharp" {...props}></Icon>
<style>
:global(.x3jdr0bzt) {
  fill: currentColor;
  d: path("m12 11.596l3.173-3.192H8.827zM5 15h14V5H5zm-1 5V4h16v16z");
}

</style>
