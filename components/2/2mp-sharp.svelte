<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3703acee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:2mp-sharp" {...props}></Icon>
<style>
:global(.f3703acee) {
  fill: currentColor;
  d: path("M6 18.5h1.5V14h1v3H10v-3h1v4.5h1.5v-6H6zm3.75-7h4.5V10h-3V9h3V5.5h-4.5V7h3v1h-3zm3.75 7H15V17h3v-4.5h-4.5zm1.5-3V14h1.5v1.5zM3 21V3h18v18z");
}

</style>
