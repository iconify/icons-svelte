<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgc2hnbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:meeting-room-sharp" {...props}></Icon>
<style>
:global(.dgc2hnbvt) {
  fill: currentColor;
  d: path("M3 21v-2h2V3h10v1h4v15h2v2h-4V6h-2v15zm8.713-8.287Q12 12.425 12 12t-.288-.712T11 11t-.712.288T10 12t.288.713T11 13t.713-.288");
}

</style>
