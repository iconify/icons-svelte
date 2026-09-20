<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo9d67tkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:propane-sharp" {...props}></Icon>
<style>
:global(.fo9d67tkv) {
  fill: currentColor;
  d: path("M10 6h4V5h-4zM7 21v-3q-2.5 0-4.25-1.75T1 12t1.75-4.25T7 6h1V3h8v3h1q2.5 0 4.25 1.75T23 12t-1.75 4.25T17 18v3h-2v-3H9v3z");
}

</style>
