<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9mw98ilc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:network-cell-sharp" {...props}></Icon>
<style>
:global(.y9mw98ilc) {
  fill: currentColor;
  d: path("M2 22L22 2v20zm15-2h3V6.85l-3 3z");
}

</style>
