<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f35jv97gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-outward-outline-sharp" {...props}></Icon>
<style>
:global(.f35jv97gg) {
  fill: currentColor;
  d: path("M6.189 17.289L5.5 16.6L15.58 6.5H6.289v-1h11v11h-1V7.208z");
}

</style>
