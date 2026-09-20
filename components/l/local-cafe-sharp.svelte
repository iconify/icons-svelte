<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_h7xqgow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:local-cafe-sharp" {...props}></Icon>
<style>
:global(.h_h7xqgow) {
  fill: currentColor;
  d: path("M5 20v-1h14v1zm0-3.77V4h16v5.5h-3.692v6.73zM17.308 8.5H20V5h-2.692z");
}

</style>
