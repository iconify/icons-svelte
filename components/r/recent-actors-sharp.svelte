<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxanupq_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:recent-actors-sharp" {...props}></Icon>
<style>
:global(.oxanupq_k) {
  fill: currentColor;
  d: path("M1 19V5h14v14zm2-3.65q1.1-.65 2.35-1T8 14t2.65.35t2.35 1V7H3zm3.05-2.9q-.8-.8-.8-1.95t.8-1.95T8 7.75t1.95.8t.8 1.95t-.8 1.95t-1.95.8t-1.95-.8M17 19V5h2v14zm4 0V5h2v14z");
}

</style>
