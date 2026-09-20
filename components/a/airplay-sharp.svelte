<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epuj6y-rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:airplay-sharp" {...props}></Icon>
<style>
:global(.epuj6y-rw) {
  fill: currentColor;
  d: path("M7.423 20L12 15.423L16.577 20zM3 18V4h18v14h-3l-6-6l-6 6z");
}

</style>
