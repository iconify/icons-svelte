<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cytol_8_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-21-9-sharp" {...props}></Icon>
<style>
:global(.cytol_8_c) {
  fill: currentColor;
  d: path("M3 16V8h18v8z");
}

</style>
