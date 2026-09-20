<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_eqm4hkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:notes-outline-sharp" {...props}></Icon>
<style>
:global(.c_eqm4hkc) {
  fill: currentColor;
  d: path("M3 18v-2h12v2zm0-5v-2h18v2zm0-5V6h18v2z");
}

</style>
