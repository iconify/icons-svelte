<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru6jlnxtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:checklist-rtl-outline-rounded" {...props}></Icon>
<style>
:global(.ru6jlnxtn) {
  fill: currentColor;
  d: path("m16.35 16.175l3.55-3.55q.3-.3.7-.288t.7.313q.275.3.275.7t-.275.7l-4.225 4.25q-.3.3-.7.3t-.7-.3l-2.15-2.15q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275zm0-8l3.55-3.55q.3-.3.7-.288t.7.313q.275.3.275.7t-.275.7l-4.225 4.25q-.3.3-.7.3t-.7-.3l-2.15-2.15q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275zM3 17q-.425 0-.712-.288T2 16t.288-.712T3 15h7q.425 0 .713.288T11 16t-.288.713T10 17zm0-8q-.425 0-.712-.288T2 8t.288-.712T3 7h7q.425 0 .713.288T11 8t-.288.713T10 9z");
}

</style>
