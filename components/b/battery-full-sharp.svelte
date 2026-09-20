<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd57mfbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-full-sharp" {...props}></Icon>
<style>
:global(.jd57mfbtj) {
  fill: currentColor;
  d: path("M7 22V4h3V2h4v2h3v18z");
}

</style>
