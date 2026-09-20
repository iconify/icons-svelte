<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgb9agavc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:add-diamond-sharp" {...props}></Icon>
<style>
:global(.qgb9agavc) {
  fill: currentColor;
  d: path("M11 16h2v-3h3v-2h-3V8h-2v3H8v2h3zm1.025 6.85L1.225 12l10.8-10.825L22.775 12z");
}

</style>
