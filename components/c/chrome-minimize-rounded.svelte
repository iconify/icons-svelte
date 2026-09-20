<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gripr69wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chrome-minimize-rounded" {...props}></Icon>
<style>
:global(.gripr69wu) {
  fill: currentColor;
  d: path("M5 20q-.425 0-.713-.288T4 19q0-.425.288-.713T5 18h14q.425 0 .713.288T20 19q0 .425-.288.713T19 20H5Z");
}

</style>
