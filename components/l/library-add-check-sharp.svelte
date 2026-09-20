<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix7xjtatz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:library-add-check-sharp" {...props}></Icon>
<style>
:global(.ix7xjtatz) {
  fill: currentColor;
  d: path("m12.7 14.05l5.65-5.65l-1.4-1.45l-4.25 4.25l-2.15-2.1l-1.4 1.4zM6 18V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
