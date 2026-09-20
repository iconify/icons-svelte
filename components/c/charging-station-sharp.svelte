<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxsnc_twd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:charging-station-sharp" {...props}></Icon>
<style>
:global(.fxsnc_twd) {
  fill: currentColor;
  d: path("M11.5 17v-4h-2l3-6v4h2zM5 23V1h14v22zm2-5h10V6H7z");
}

</style>
