<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oatzu2k0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-horiz-075-outline-sharp" {...props}></Icon>
<style>
:global(.oatzu2k0q) {
  fill: currentColor;
  d: path("M4 17v-3H2v-4h2V7h18v10zm2-2h4V9H6z");
}

</style>
