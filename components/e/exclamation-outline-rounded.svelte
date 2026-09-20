<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-jo4d_6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:exclamation-outline-rounded" {...props}></Icon>
<style>
:global(.q-jo4d_6e) {
  fill: currentColor;
  d: path("M11.288 13.713Q11 13.425 11 13V6q0-.425.288-.712T12 5t.713.288T13 6v7q0 .425-.288.713T12 14t-.712-.288m0 5Q11 18.426 11 18t.288-.712T12 17t.713.288T13 18t-.288.713T12 19t-.712-.288");
}

</style>
