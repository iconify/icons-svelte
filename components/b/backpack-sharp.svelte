<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpzhyojuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:backpack-sharp" {...props}></Icon>
<style>
:global(.zpzhyojuw) {
  fill: currentColor;
  d: path("M4 22V8q0-1.4.85-2.45T7 4.15V2h3v2h4V2h3v2.15q1.3.35 2.15 1.4T20 8v14zm10.5-6h2v-4h-9v2h7z");
}

</style>
