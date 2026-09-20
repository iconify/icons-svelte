<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eld51ebxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:navigation-sharp" {...props}></Icon>
<style>
:global(.eld51ebxl) {
  fill: currentColor;
  d: path("m5.962 19.5l-.462-.423L12 4.462l6.5 14.615l-.462.423L12 16.923z");
}

</style>
