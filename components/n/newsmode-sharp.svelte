<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxg571b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:newsmode-sharp" {...props}></Icon>
<style>
:global(.jxg571b9c) {
  fill: currentColor;
  d: path("M2 21V3h20v18zm4-4h12v-2H6zm0-4h4V7H6zm6 0h6v-2h-6zm0-4h6V7h-6z");
}

</style>
