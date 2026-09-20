<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggiwukspm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-option-key-outline-sharp" {...props}></Icon>
<style>
:global(.ggiwukspm) {
  fill: currentColor;
  d: path("m15.064 18.5l-6.926-12H4v-1h4.712l6.925 12H20v1zm.436-12v-1H20v1z");
}

</style>
