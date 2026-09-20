<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-vgycc8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:horizontal-rule-outline-rounded" {...props}></Icon>
<style>
:global(.s-vgycc8v) {
  fill: currentColor;
  d: path("M5 13q-.425 0-.712-.288T4 12t.288-.712T5 11h14q.425 0 .713.288T20 12t-.288.713T19 13z");
}

</style>
