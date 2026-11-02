<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2qkh7b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-checklist-fill-round" {...props}></Icon>
<style>
:global(.z2qkh7b8f) {
  fill: currentColor;
  d: path("M3.707 5.293L5 6.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414M13 5h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2m-9.293 6.293L5 12.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414M13 11h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2m-9.293 6.293L5 18.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a1 1 0 0 1 1.414-1.414M13 17h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
