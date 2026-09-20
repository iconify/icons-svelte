<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhe0glbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:difference-sharp" {...props}></Icon>
<style>
:global(.vhe0glbcl) {
  fill: currentColor;
  d: path("M12.5 11h2V9h2V7h-2V5h-2v2h-2v2h2zm-2 4h6v-2h-6zM6 19V1h9l6 6v12zm-4 4V7h2v14h11v2z");
}

</style>
