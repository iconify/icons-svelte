<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj8joy8nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:door-back-outline-sharp" {...props}></Icon>
<style>
:global(.wj8joy8nz) {
  fill: currentColor;
  d: path("M3 21v-2h2V3h14v16h2v2zm4-2h10V5H7zm3-6q.425 0 .713-.288T11 12t-.288-.712T10 11t-.712.288T9 12t.288.713T10 13M7 5v14z");
}

</style>
