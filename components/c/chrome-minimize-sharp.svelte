<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8rg3ebrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chrome-minimize-sharp" {...props}></Icon>
<style>
:global(.t8rg3ebrj) {
  fill: currentColor;
  d: path("M4 20v-2h16v2Z");
}

</style>
