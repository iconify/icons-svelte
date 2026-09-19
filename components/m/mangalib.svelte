<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="liawmobsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mangalib" {...props}></Icon>
<style>
:global(.liawmobsl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 18.5v-9a4 4 0 0 1 4-4h9m24 24v9a4 4 0 0 1-4 4h-9m-16-8.023V13.5l10.5 21l10.5-20.968V34.5");
}

</style>
