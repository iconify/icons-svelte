<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccmaxdsxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:auto-awesome-motion-sharp" {...props}></Icon>
<style>
:global(.ccmaxdsxo) {
  fill: currentColor;
  d: path("M11 21V11h10v10zm-4-3.77V7h10.23v1H8v9.23zm-4-4V3h10.23v1H4v9.23z");
}

</style>
