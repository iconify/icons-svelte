<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id5ywyrnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-horiz-000" {...props}></Icon>
<style>
:global(.id5ywyrnv) {
  fill: currentColor;
  d: path("M5 17q-.425 0-.712-.288T4 16v-2H2v-4h2V8q0-.425.288-.712T5 7h16q.425 0 .713.288T22 8v8q0 .425-.288.713T21 17zm1-2h14V9H6z");
}

</style>
