<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kayxdc_nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chrome-minimize" {...props}></Icon>
<style>
:global(.kayxdc_nz) {
  fill: currentColor;
  d: path("M4 20v-2h16v2H4Z");
}

</style>
