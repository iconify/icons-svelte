<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_whpiodg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pallet-sharp" {...props}></Icon>
<style>
:global(.v_whpiodg) {
  fill: currentColor;
  d: path("M2 22v-4h20v4h-3v-2h-5.5v2h-3v-2H5v2zm3-6V2h14v14zm4-8h6V6H9z");
}

</style>
