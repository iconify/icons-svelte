<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5w-hzb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:event-note-sharp" {...props}></Icon>
<style>
:global(.l5w-hzb3d) {
  fill: currentColor;
  d: path("M7.5 13.5v-1h9v1zm0 4v-1h6v1zM4 21V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v16zm1-1h14v-9.384H5z");
}

</style>
