<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-g0qac3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:all-inbox-sharp" {...props}></Icon>
<style>
:global(.r-g0qac3b) {
  fill: currentColor;
  d: path("M14 13q.85 0 1.425-.587T16 11h4V4H8v7h4q0 .825.588 1.413T14 13m-8 5V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
