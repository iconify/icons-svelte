<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-fxrg6hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-2-3-sharp" {...props}></Icon>
<style>
:global(.f-fxrg6hz) {
  fill: currentColor;
  d: path("M6 22V2h12v20z");
}

</style>
