<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkrobmw2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:door-back-sharp" {...props}></Icon>
<style>
:global(.fkrobmw2a) {
  fill: currentColor;
  d: path("M3 21v-2h2V3h14v16h2v2zm7.713-8.287Q11 12.425 11 12t-.288-.712T10 11t-.712.288T9 12t.288.713T10 13t.713-.288");
}

</style>
