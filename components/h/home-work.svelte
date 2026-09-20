<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plo8bo3fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:home-work" {...props}></Icon>
<style>
:global(.plo8bo3fq) {
  fill: currentColor;
  d: path("M17 9h2V7h-2zm0 4h2v-2h-2zm0 4h2v-2h-2zM1 21V11l7-5l7 5v10h-5v-6H6v6zm16 0V10l-7-5.05V3h13v18z");
}

</style>
