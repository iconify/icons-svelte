<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei849gtbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-stretch-sharp" {...props}></Icon>
<style>
:global(.ei849gtbg) {
  fill: currentColor;
  d: path("M7 10V4H2V2h20v2h-5v6zM2 22v-2h5v-6h10v6h5v2z");
}

</style>
