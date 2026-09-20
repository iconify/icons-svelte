<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om4rwrhqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chat-info-sharp" {...props}></Icon>
<style>
:global(.om4rwrhqe) {
  fill: currentColor;
  d: path("M12 7q.425 0 .713-.288T13 6t-.288-.712T12 5t-.712.288T11 6t.288.713T12 7m-1 8h2V9h-2zm-9 7V2h20v16H6z");
}

</style>
