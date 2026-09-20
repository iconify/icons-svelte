<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spu0rnuec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:move-selection-left-outline-sharp" {...props}></Icon>
<style>
:global(.spu0rnuec) {
  fill: currentColor;
  d: path("M2 18V6h12v12zm2-2h8V8H4zm12-8V6h2v2zm0 10v-2h2v2zm4-10V6h2v2zm0 5v-2h2v2zm0 5v-2h2v2zM8 12");
}

</style>
