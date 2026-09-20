<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh8ry1bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:collapse-content-outline" {...props}></Icon>
<style>
:global(.wh8ry1bdn) {
  fill: currentColor;
  d: path("M11 13v6H9v-4H5v-2zm4-8v4h4v2h-6V5z");
}

</style>
