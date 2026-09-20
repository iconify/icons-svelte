<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l67a8ebfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-portrait-sharp" {...props}></Icon>
<style>
:global(.l67a8ebfv) {
  fill: currentColor;
  d: path("M5 21V3h14v18z");
}

</style>
