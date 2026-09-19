<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es2vlq-8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:perm-device-information" {...props}></Icon>
<style>
:global(.es2vlq-8n) {
  fill: currentColor;
  d: path("M13 7h-2v2h2zm0 4h-2v6h2zm4-9.99L7 1c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99M17 19H7V5h10z");
}

</style>
