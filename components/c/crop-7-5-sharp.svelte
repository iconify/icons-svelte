<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygtvc5brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-7-5-sharp" {...props}></Icon>
<style>
:global(.ygtvc5brp) {
  fill: currentColor;
  d: path("M4 18V6h16v12z");
}

</style>
