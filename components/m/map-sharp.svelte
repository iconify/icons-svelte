<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcvjx2bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:map-sharp" {...props}></Icon>
<style>
:global(.qcvjx2bjo) {
  fill: currentColor;
  d: path("m15 21l-6-2.1l-6 2.325V5.05L9 3l6 2.1l6-2.325V18.95zm-1-2.45V6.85l-4-1.4v11.7z");
}

</style>
