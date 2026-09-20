<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4f2ows3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-full-outline-sharp" {...props}></Icon>
<style>
:global(.r4f2ows3v) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-5h16V6H4z");
}

</style>
