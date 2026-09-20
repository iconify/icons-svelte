<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo2c33bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:magnification-large-outline-sharp" {...props}></Icon>
<style>
:global(.mo2c33bvl) {
  fill: currentColor;
  d: path("M5.5 14.5h11v-7h-11zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
