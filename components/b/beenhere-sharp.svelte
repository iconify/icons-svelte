<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7u50fbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:beenhere-sharp" {...props}></Icon>
<style>
:global(.k7u50fbca) {
  fill: currentColor;
  d: path("m12 23l-8-6V2h16v15zm-1.05-8l5.65-5.65l-1.4-1.45l-4.25 4.25l-2.1-2.1l-1.45 1.4z");
}

</style>
