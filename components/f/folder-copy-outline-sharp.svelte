<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9uj_eotm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:folder-copy-outline-sharp" {...props}></Icon>
<style>
:global(.g9uj_eotm) {
  fill: currentColor;
  d: path("M1 21V6h2v13h17v2zm4-4V2h7l2 2h9v13zm2-2h14V6h-7.825l-2-2H7zm0 0V4z");
}

</style>
