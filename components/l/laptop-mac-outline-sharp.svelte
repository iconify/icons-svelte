<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmmejeksx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:laptop-mac-outline-sharp" {...props}></Icon>
<style>
:global(.fmmejeksx) {
  fill: currentColor;
  d: path("M0 20v-2h3l-1-1V3h20v14l-1 1h3v2zm12.713-1.287Q13 18.425 13 18t-.288-.712T12 17t-.712.288T11 18t.288.713T12 19t.713-.288M4 16h16V5H4zm0 0V5z");
}

</style>
