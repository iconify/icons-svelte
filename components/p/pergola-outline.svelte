<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qonabt9et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pergola-outline" {...props}></Icon>
<style>
:global(.qonabt9et) {
  fill: currentColor;
  d: path("M3 21V3q0-.425.288-.712T4 2t.713.288T5 3v1h14V3q0-.425.288-.712T20 2t.713.288T21 3v18h-2V10H5v11zM5 8h14V6H5zm6 13v-3H8v-2h8v2h-3v3zM5 8V6z");
}

</style>
