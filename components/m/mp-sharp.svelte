<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhbc-1bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mp-sharp" {...props}></Icon>
<style>
:global(.yhbc-1bjq) {
  fill: currentColor;
  d: path("M6 15h1.5v-4.5h1v3H10v-3h1V15h1.5V9H6zm7.5 0H15v-1.5h3V9h-4.5zm1.5-3v-1.5h1.5V12zM3 21V3h18v18z");
}

</style>
